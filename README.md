- š Hi, Iām @mrxyz123
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
mrxyz123/mrxyz123 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.

An Example of Inheritance;

class Shape(){

private:
  int Width;
  int Length;
public:
  virtual int AreaCalcultion()=0;
  virtual int PerimeterCalculation()=0;
}

class Square() : public Shape {
  public:
    Square(){
      Width = 1;
      Length = 1;
    }
    Square(int length){
      Width= length;
      Length= length;
    }
    
    // Method inherts from Base class
    int AreaCalcultion() {
       return length*length;
    }
    int PerimeterCalculation(){
        return length*4;
    }
        
  private:
    int Width;
    int Length;   
  } 
  
  
class Rectangle() : public Shape {
  public:
    Rectangle(){
      Width = 1;
      Length = 1;
    }
    Rectangle(int length; int width){
      Width= width;
      Length= length;
    }
    
    // Method inherts from Base class
    int AreaCalcultion() {
       return length*width;
    }
    int PerimeterCalculation(){
        return (length + width)*2;
    }
        
  private:
    int Width;
    int Length;   
  }    


}



