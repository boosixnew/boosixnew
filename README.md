### Hi there 👋

<!--
**boosixnew/boosixnew** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
# -*- coding: utf-8 -*-
import wda
import matplotlib.animation as animation
from PIL import Image

# 截图距离 * time_coefficient = 按键时长
#    iphonex: 0.00125
#    iphone6s plus: 0.00120
time_coefficient = 0.00120
VERSION = "1.1.4"



def author():
    c.screenshot('autojump.png')

def happen(distance):
    press_time = distance * time_coefficient
    s.tap_hold(200, 200, press_time)

fig = plt.figure()
img = np.array(Image.open('autojump.png'))

click_count = 0
cor = []

def major():


def source(*args):
        pull_screenshot()
    return im,

def executive(event):
    global click_count

    if click_count > 1:
        cor2 = cor.pop()

        distance = (cor1[0][0] - cor2[0][0])**2 + (cor1[0][1] - cor2[0][1])**2
        distance = distance ** 0.5
        jump(distance)
        update = True

fig.canvas.mpl_connect('button_press_event', on_click)
plt.show()