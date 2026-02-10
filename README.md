# ✧ 𝐊𝐨𝐭 𝐁𝐨𝐫𝐢𝐬 ✧ 🔮 - Магический хранитель кода

class ВолшебныйКот:
    def __init__(self):
        self.имя = "✧ 𝐊𝐨𝐭 𝐁𝐨𝐫𝐢𝐬 ✧"
        self.титул = "🔮 Хранитель Трех Языков 🔮"
        self.иконки = {
            'python': 'https://images.icon-icons.com/112/PNG/96/python_18894.png',
            'nodejs': 'https://images.icon-icons.com/2415/PNG/96/nodejs_plain_logo_icon_146409.png',
            'java': 'https://images.icon-icons.com/2415/PNG/96/java_original_wordmark_logo_icon_146459.png'
        }
    
    def показать_силу(self):
        return f"""
        <img src="{self.иконки['python']}" width="48" height="48"> | Змеиная мудрость AI-заклинаний
        <img src="{self.иконки['nodejs']}" width="48" height="48"> | Паутина асинхронных миров
        <img src="{self.иконки['java']}" width="48" height="48"> | Вечная крепость JVM-магии
        """
    
    def создать_заклинание(self):
        return f"""
        ╔═══════════════════════════════════════╗
        ║         {self.имя} АКТИВИРОВАН        ║
        ║         {self.титул}                  ║
        ╠═══════════════════════════════════════╣
        ║  <img src="{self.иконки['python']}" width="32" height="32">  •  Синтаксические иллюзии   ║
        ║  <img src="{self.иконки['nodejs']}" width="32" height="32">  •  Event-loop паутины       ║
        ║  <img src="{self.иконки['java']}" width="32" height="32">  •  Байткод-инкарнации      ║
        ╚═══════════════════════════════════════╝
        """

# Призыв кота
кот = ВолшебныйКот()
print(кот.создать_заклинание())
print("Силы кота:")
print(кот.показать_силу())
