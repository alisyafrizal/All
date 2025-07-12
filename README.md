#anchorlayout  
from kivy.app import App
from kivy.uix.button import Button
from kivy.uix.anchorlayout import AnchorLayout

class MyApp(App):
    def build(self):
        a_layout = AnchorLayout(anchor_x='center', anchor_y='center')
        
        btn = Button(text='Alisyafrizal')
        btn.size_hint = (0.2, 0.2)
        
        a_layout.add_widget(btn)
        return a_layout
MyApp().run()
