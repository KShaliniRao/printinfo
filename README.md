# printinfo

import java.io.*;

public class Employees

{

int y;

String name, adr;

BufferedReader br=new BufferedReader(newInputStreamReader(System.in));

void input();

System.out.println("Enter your year of joining");

y=Integer.parseInt(br.readLine());

System.out.println("Enter your Name");

name=br.readLine();

System.out.println("Enter your addresses");

adr=br.readLine();

}

import java.io.*;

class Company

{

public static void main()throws IOException

Employees emp=new Employees();

emp.input();

}

Read more on Brainly.in - https://brainly.in/question/8810536#readmore
