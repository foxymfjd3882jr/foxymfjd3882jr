# ✧ 𝐊𝐨𝐭 𝐁𝐨𝐫𝐢𝐬 ✧ 🔮 - Магический хранитель кода

```python
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
        python_icon = "![Python](https://images.icon-icons.com/112/PNG/96/python_18894.png)"
        nodejs_icon = "![Node.js](https://images.icon-icons.com/2415/PNG/96/nodejs_plain_logo_icon_146409.png)"
        java_icon = "![Java](https://images.icon-icons.com/2415/PNG/96/java_original_wordmark_logo_icon_146459.png)"
        
        return f"""
        {python_icon} | Змеиная мудрость AI-заклинаний
        {nodejs_icon} | Паутина асинхронных миров
        {java_icon} | Вечная крепость JVM-магии
        """
    
    def создать_заклинание(self):
        return f"""
        ╔═══════════════════════════════════════╗
        ║         {self.имя} АКТИВИРОВАН        ║
        ║         {self.титул}                  ║
        ╠═══════════════════════════════════════╣
        ║  ![Py](https://images.icon-icons.com/112/PNG/32/python_18894.png)  •  Синтаксические иллюзии   ║
        ║  ![Node](https://images.icon-icons.com/2415/PNG/32/nodejs_plain_logo_icon_146409.png)  •  Event-loop паутины ║
        ║  ![Java](https://images.icon-icons.com/2415/PNG/32/java_original_wordmark_logo_icon_146459.png)  •  Байткод-инкарнации ║
        ╚═══════════════════════════════════════╝
        """

# Призыв кота
кот = ВолшебныйКот()
print(кот.создать_заклинание())
print("Силы кота:")
print(кот.показать_силу())
