# dart-time
dart-time
class Time



void main() {
 
    
  // constructor time set
   var object7=Time.t1(12,45,20);
  object7.displayTime();
   var object10=Time();
   object10.displayTime();
    var object11=Time.t2(10,45,20);
   object11.displayTime();
  
  //function time set
   var object12=Time();
  object12.settime(12,4,5);
  object12.displayTime();
  
  
} //voidddddddddddddddddddddddd   end

class Time 
{ late int hr;
late int min;
late int seconds;
Time()
  
{
  this.hr=00;
  this.min=00;
  this.seconds=00;
  
  
}
 
 Time.t1(int hrs,int mins,int secs)
 {
   
   if(hrs<=24)
   {
     this.hr=hrs;
    
   }
   else{
     
     this.hr=00;
   }
    if(mins<=60)
   {
     this.min=mins;
    
   }
   else{
     
     this.min=00;
   }
   
    if(secs<=60)
   {
     this.seconds=secs;
    
   }
   else{
     
     this.seconds=00;
   }
   
   
   
 }
 
 
 
  Time.t2(int hrs,int mins,int secs)
 {
   
   if(hrs<=24)
   {
     this.hr=hrs;
    
   }
   else{
     
     this.hr=00;
   }
    if(mins<=60)
   {
     this.min=mins;
    
   }
   else{
     
     this.min=00;
   }
   
    if(secs<=60)
   {
     this.seconds=secs;
    
   }
   else{
     
     this.seconds=00;
   }
   
   
   
 }
 
 
  void settime(int hrs,int mins,int secs)
 {
   
   if(hrs<=24)
   {
     this.hr=hrs;
    
   }
   else{
     
     this.hr=00;
   }
    if(mins<=60)
   {
     this.min=mins;
    
   }
   else{
     
     this.min=00;
   }
   
    if(secs<=60)
   {
     this.seconds=secs;
    
   }
   else{
     
     this.seconds=00;
   }
   
   
   
 }
 
 
 
 
 
 
 
 displayTime()
 {
   print("hours : $hr mint : $min   seconds : $seconds" );
    
    
   
 }
  


}


