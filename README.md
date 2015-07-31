# core-java
class Are { double r,A; void getdata(double x) { r=x; } public void putdata() { A=r*r*3.14; System.out.println("area is: "+A); } } class Are1 { public static void main(String args[]) { Are a1=new Are(); double xx=Double.parseDouble(args[0]); a1.getdata(xx); a1.putdata(); } }
