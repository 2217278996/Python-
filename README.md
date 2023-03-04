# Python-class Snow():    #雪花类
    def __init__(self):
        self.r = 6                       #雪花的半径
        self.x = ra.randint(-1000,1000)   #雪花的横坐标
        self.y = ra.randint(-500,500)     #雪花的纵坐标
        self.f = ra.uniform(-3.14,3.14)   #雪花左右移动呈正弦函数
        self.speed = ra.randint(5,10)     #雪花移动速度
        self.color = ra.choice(colors)    #雪花的颜色
        self.outline = 5                 #雪花的大小 
