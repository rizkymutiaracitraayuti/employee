package utspbo;

public class employee {
    String name = "";
    int idNumber = 0;
    String department = "";
    String position = "";
    
    
    public employee( String name, int idNumber, String department, String position){
        this.name = name; 
        this.idNumber = idNumber;
        this.department = department;
        this.position = position;
    }
    
    public static void main(String[] args) {
        employee em1 = new employee ("Susan Meyers", 47899, "Accounting", "Vice President");
        employee em2 = new employee ("Mark Jones", 39119, "IT", "Proggramer");
        employee em3 = new employee ("Joy Rogers", 81774, "Manufacturing", "Engineer");
        
        System.out.println(em1.name +"\t"+ em1.idNumber +"\t"+ em1.department +"\t"+ em1.position);
        System.out.println(em2.name +"\t"+ em2.idNumber +"\t"+ em2.department +"\t\t"+ em2.position);
        System.out.println(em3.name +"\t"+ em3.idNumber +"\t"+ em3.department +"\t"+ em3.position);
    }
}
