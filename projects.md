Back to [Home](README.md)

### Long Hunt Series
(Working title)  
A theoretical series of books involving a world in which monsters have overrun, neccistating the creation of an organization of monster hunters, which then used that as an excuse to take over

### "Dndish game"
(Working title)  
A theoretical game involving mecahnics similar to those of the roleplay game Dungeons and Dragons. Originally started in Python, switched over to java when I started learning that   
Example code:
```
public int disadvantage()
  {
    int d1=Dice.d20();
    System.out.println("First roll: " +d1+"\n");
    int d2= Dice.d20();
    System.out.println("Second roll: " +d2+"\n");
    Thread.sleep(2000);
    if(d1>=d2)
    {
      System.out.println("Advantage: "+ d2+"\n");
      return d2;
    }
    System.out.println("Advantage: "+ d1+"\n");
    return d1;
  }
```
