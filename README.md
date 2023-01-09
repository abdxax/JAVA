# JAVA

 public static void main(String[] args) {
        Scanner scanner=new Scanner(System.in);
        System.out.println("Q1");
        //1-Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers.
        System.out.println("Enter First Number");
        int num1=scanner.nextInt();
        System.out.println("Enter Second Number");
        int num2=scanner.nextInt();
        System.out.println(num1+"+"+num2+"="+(num1+num2));
        System.out.println(num1+"-"+num2+"="+(num1-num2));
        System.out.println(num1+"*"+num2+"="+(num1*num2));
        System.out.println(num1+"/"+num2+"="+(num1/num2));
        System.out.println(num1+"%"+num2+"="+(num1%num2));

        System.out.println("Q2");
        //2-2.Write a Java program to convert a given string into lowercase.
        String str="THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG";
        System.out.println(str.toLowerCase());

        System.out.println("Q3");

        int numDigt=scanner.nextInt();

        System.out.println("Q3");
        //3.Write a Java program to reverse a string.
        String str2="The quick brown fox";
        for(int i=str2.length();i>=0;i--){
            System.out.print(str.charAt(i));
        }

        System.out.println("Q4");
        //4.Write a Java program to accept a number and check the number is even or not. Prints 1 if the number is even or 0 if the number is odd. (use if-statement)
        System.out.println("Enter The Number");
        int cnum=scanner.nextInt();
        if(cnum%2==0){
            System.out.println("1");
        }
        else{
            System.out.println("0");
        }

        System.out.println("Q5");
        //5.Write a program that checks the role of the user
        System.out.println();
        System.out.println("Enter the role ");
        scanner.nextLine();
        String role=scanner.nextLine();
        if(role.equals("admin")){
            System.out.println("welcome admin");
        } else if (role.equals("superuser")) {
            System.out.println("welcome superuser");
        }
        else if(role.equals("user")){
            System.out.println("welcome user");
        }
        else{
            System.out.println("welcome ");
        }

        System.out.println("Q6");
        //6.Write a Java program to calculate the sum of two integers and return true if the sum is equal to a third integer.
        System.out.println("Please Enter first diget");
        int diget1=scanner.nextInt();
        System.out.println("Please Enter second diget");
        int diget2=scanner.nextInt();
        System.out.println("Please Enter third diget");
        int diget3=scanner.nextInt();
        int sum=diget1+diget2;
        if(sum==diget3){
            System.out.println(true);
        }
        else{
            System.out.println(false);
        }

        System.out.println("Q7");
        //7.Take three numbers from the user and print the greatest number.
        System.out.println("Please Enter first diget");
        int d1=scanner.nextInt();
        System.out.println("Please Enter second diget");
        int d2=scanner.nextInt();
        System.out.println("Please Enter third diget");
        int d3=scanner.nextInt();
        int great=d1;
        if(d1<d2){
            great=d2;
        }
        if(great<d3){
            great=d3;
        }
        System.out.println("The greatest:"+great);

        System.out.println("Q8");
         //8.Write a Java program that keeps a number from the user and generates an integer between 1 and 7 and displays the name of the weekday.
        System.out.println("Please Enter number of day");
        int day=scanner.nextInt();
        switch (day){
            case 1:
                System.out.println("Sunday");
                break;
            case 2:
                System.out.println("Monday");
                break;
            case 3:
                System.out.println("Tuesday");
                break;
            case 4:
                System.out.println("Wednesday");
                break;

            case 5:
                System.out.println("Thursday");
                break;
            case 6:
                System.out.println("Friday");
                break;
            case 7:
                System.out.println("Saturday");
                break;
            default:
                System.out.println("Error choice");
                break;
        }
    }
