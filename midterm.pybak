def totalBill(checkAmount):
   tip=checkAmount*0.15
   print checkAmount+tip

def question4():
  color= makeColor(18,52,86)
  pic=makeEmptyPicture(200,200,color)
  show (pic)

def question5(fib):
  digit1=1
  digit2=0
  digit3=0
  
  print digit1
  for counter in range(0,fib-1):
    digit3=digit2
    digit2=digit1
    digit1=digit3+digit2
    print digit1
    
def question13():
  file=pickAFile()
  pic=makePicture(file)
  for p in getPixels(pic):
    red=getRed(p)
    green=getGreen(p)
    blue=getBlue(p)
    d=sqrt((red*red)+(green*green)+(blue*blue))
    if d>222:
      setColor(p,white)
    else:
      setColor(p,black)
  show(pic)
    

def question6 (fib): 
  d1=1
  d2=2
  fibList=[]
  if fib>0:
    fibList.append(d1)
  if fib>1:
    fibList.append(d2)
  for num in range(0,(fib-2)):
    v=d1+d2
    fibList.append(v)
    di=d2
    d2=v
  print fibList 
 
    

def question7():
  pic=makeEmptyPicture(800,800,white)
  blackPic = makeEmptyPicture(100,100,black)
  for row in range (0,8,2):
    for col in range(1,8,2):
      copyInto(blackPic,pic,col*100,row*100)
  for row in range(1,8,2):
    for col in range(0,8,2):
      copyInto(blackPic,pic,col*100, row*100)
  show (pic)




def question11():
  file=pickAFile()
  pic=makePicture(file)
  for p in getPixels(pic):
    red=getRed(p)
    green=getGreen(p)
    blue=getBlue(p)
    color=makeColor(red-255,green,blue)
    setColor(p,color)
  show(pic)

def drawCircle(pic,diameter):
  for i in range (628):
    x=diameter*cos(2*pi*i/628)+150
    y=diameter*sin(2*pi*i/628)+150
  p = getPixel(pic,int(x),int(y))
  setColor(p,black)
 
def colorCenter(pic,diameter):
  for p in getPixels(pic):
    if sqrt (pow(getX(p)-150,2)+pow(getY(p)-150,2))<diameter:
      setColor(p,red)

def question17():
  pic=makeEmptyPicture(200,200)
  drawCircle(pic,25)
  drawCircle(pic,50)
  drawCircle(pic,75)
  drawCircle(pic,100)
  colorCenter(pick,25)
  show (pic)
  
def drawX(pic):
  for v in range(300):
    p=getPixel(pic,v,v)
    setColor(p,black)
    px=getPixel(pic,v,299-v)
    setColor(px,black)

def drawPlus(pic):
  for x in range(150,151):
    for y in range (0, getHeight(pic)):
      p=getPixel (pic,x,y)
      setColor(p,black)
  for y in range (150,151):
    for x in range(0,getWidth(pic)):
      p=getPixel(pic,x,y)
      setColor (p,black) 

def question19():
  pic=makeEmptyPicture(300,300)
  drawCircle(pic,25)
  drawCircle(pic,50)
  drawCircle(pic,75)
  drawCircle(pic,100)
  colorCenter(pic,25)
  drawX(pic)
  drawPlus(pic)
  show(pic)


def question18():
  pic=makeEmptyPicture(300,300)
  drawCircle(pic,25)
  drawCircle (pic,50)
  drawCircle (pic,75)
  drawCircle(pic,100)
  colorCenter(pic,25)
  drawX(pic)
  show(pic)
def function(x,y):
  print functionB(x)
  print functionB(y)
def functionB(a):
  return a*a

  