# **Viktoryia Kurs**
###### contact: Warsaw, Poland | +48 796 011 437 | vikakurs1998@gmail.com ######
######  https://github.com/ViktoryiaKurs | https://t.me/ViktoryiaKurs | discord: viktoryia.kurs ######
##  About Me
I am an aspiring software developer currently building a solid foundation in Full Stack JavaScript at RS School. Crucially, I already possess a strong standalone background in **Java Core and OOP principles**, having successfully completed comprehensive programmatic training. This architectural foundation, combined with my past professional experience in accounting, logistics, and HR, equips me with advanced analytical thinking and a structured approach to engineering.

My goal is to leverage my Java background to master both frontend and backend web technologies. My greatest strength is the ability to rapidly digest complex new domains. I am highly motivated, ready to contribute to real-world tasks, and dedicated to evolving into a versatile Full Stack professional.
##  Technical Skills
* **Programming Languages:** Java (Java Core, OOP principles)
* **Web Technologies:** HTML5, CSS3, Markdown
* **Tools & Environment:** Git, GitHub, Visual Studio Code, netbeans, IntelliJ IDEA.
##  Education & Courses
### Courses & Certifications
* **Java for Beginners: From Scratch to Oracle Certification** | *Instructor: Zaur Tregulov (Udemy)*
* **JAVA – Earn Your Black Belt!** | *Instructor: Zaur Tregulov (Udemy)*
* **A Gentle Introduction to Java: A Beginner's Course** | *Stepik Platform*
* **Full-Stack JavaScript Q3** | *RS School (In Progress, 2026)*
### Academic Education
* **Bobruisk Agrarian and Economic College**
  * *Specialty:* Accounting, Analysis and Audit
  * *Degree:* Associate Degree / Professional Diploma
  ## Languages
* **Russian:** Native / C2
* **English:** Elementary / A2 (Actively improving)
* **Polish:** Elementary / A2 (Actively improving)
## Code Example
~~~
class Student implements Comparable {
private int id;
private String name;
private String surname;
Student (int id,String name, String surname){
this.id =id;
this.name =name;
this.surname=surname;
}

@Override
public int compareTo(Student otherStudent) {
    if (this.id < otherStudent.id) {
return -1;
} else if (this.id > otherStudent.id) {
return 1;
} else {
return 0;
        }
    }
}

Class Main {
	public static void main(String[] args) {
		ArrayList<Student> students = new ArrayList<>();
		
		students.add(new Student(1, “Vika”, “Carter”));
		students.add(new Student(5, “Vlad”, “Beginer”));
		students.add(new Student(3, “Vika”, “Kurs”));
		Collections.sort (students);

	}
}

class CompareByName implements Comparator {
@Override
public int compare(Student student1,Student student2) {
	int res = student1.name.compareTo(student2.name);
if(res == 0) {
	res = student.surname.compareTo(student2.surname);
}
return res;	
    }
}
~~~
## PROFESSIONAL EXPERIENCE
* **Customer Service Specialist | BądżTu,Warsaw, Poland**
November 2023 - present

* **Freight Forwarder | BELTS, Warsaw, Poland**
August 2021 – November 2023

* **Administrative Assistant | Transconsult Service, Brest, Belarus**
October 2019 – August 2021

* **HR Inspector | OZTM S.A., Mogilev, Belarus**
February 2018 – August 2019

* **Accountant | Machowo Sp. z o.o., Mogilev, Belarus**
August 2017 – February 2018

