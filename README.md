import java.applet.*;
import java.awt.*;
import java.io.*;

public class Main extends Applet
{
    public void paint(Graphics g)
    {
        //Creating Pen Color
        //Syntax : Color Color_Object_Name = New Color(R,G,B);  
        //Color Value Max(R=255) Min(R=0)
        Color c1=new Color(0,0,0);  //New Color Created
        g.setColor(c1);
        //Create Font Style & Size 
        //Syntax : Font Font_Object_Name = New Font("Font_Name",Style,Size);
        Font f1=new Font("Comic Sans MS",Font.BOLD,50);
        g.setFont(f1);
        //Graphic_Painter_Name.drawString("String",int x,int y);
        g.drawString("Welcome To Applet Programming.....",50,50);
        g.drawString("Applet is a One of The Frame Work in Java...",100,150);
        
        Color c2=new Color(100,50,255);
        g.setColor(c2);
        g.drawString("Welcome To Applet Programming.....",45,50);
        
        Font f2=new Font("Forte",Font.BOLD,55);
        g.setFont(f2);
        g.drawString("Changing The Font Style of The Painter",20,250);
    }
}
