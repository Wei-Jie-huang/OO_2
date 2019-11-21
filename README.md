# 0624032 黃偉傑

## 0624032 黃偉傑

### **0624032 黃偉傑**

#### *0624032 黃偉傑*

##### ~~0624032 黃偉傑~~

###### 0624032 黃偉傑

###### 小組成員:
```
* 0624032 黃偉傑
* 0624058 陳宗順
* 0624076 賴炳維
* 0624098 江維欣
```
***

:tongue:

***

:beers:

***

:hatched_chick:

***

[高科大](https://www.nkust.edu.tw/)

| First | Second | Third |
|:------|:------:|------:|
|1 | 2 | 3  |
|1 | 2 | 3  |

![curry.jpg](curry.jpg "pu")

[![Everything Is AWESOME](https://img.youtube.com/vi/StTqXEQ2l-Y/0.jpg)](https://www.youtube.com/watch?v=StTqXEQ2l-Y "Everything Is AWESOME")

***

# CShape

abstract class CShape
{
  protected String color;
  public void setColor(String str)
  {
     coloe=str;
  }
  public abstract void show();
}
class CTriangle extends CShape
{
  protected double a,b,c;
  public CTriangle(double a,double b,double c)
  {
    bottom=a;
    height=b;
    hypotenuse=c;
  }
  public void show()
  {
   System.out.print("color="+color+"", ");
   System.out.println("area="+0.5*bottom*height);
  }
}  
public class homework
{
  public static void main(String args[])
  {
    CTriangle rect=new CTriangle(3,4,5);
    rect.setColor("Red");
    rect.show();
}    
