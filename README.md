# zhangshuo12

public class Test {
	
	public static void main(String[] args) {  
        
        Graduate g=new Graduate("同学");       
        g.setFee(1000);                       
          
        University u=new University();         
        u.payOff(g);                         
        System.out.println("是否满足付款要求"+g.isLoan());  
          
        Teacher t=new Teacher("老师");  
        u.payOff(t);             
    }  
 
}
