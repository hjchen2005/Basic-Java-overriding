public class Overriding {
    private static Employee employee;

	public static class Employee {  
        private String mobile;
        public Employee(String mobile) {  
            this.mobile = mobile;  
        }    
        protected String showMess(){  
            return "Phone："+mobile;  
        }  
    }  
    public static class Sales extends Employee{  
        
    	// Child can have its own properties
    	private String msn;  
    	public Sales(String mobile,String msn) {  
    		super(mobile);  
    		this.msn = msn;  
    	}  
  
    	@Override  
    	public String showMess() {  
    		return super.showMess()+"==msn:"+this.msn;  
    	}  
    }  
