package com.back;

import java.util.Scanner;

public class Main {
    public static void main(String[] arges) {


        Scanner sc = new Scanner(System.in);

        System.out.println("== 명언 앱 ==");
        System.out.println("명령) ");
        sc.nextLine(); // 입력값 받기

         while(true) {
            System.out.print("명령) ");
            String command = sc.nextLine();

            if(command.equals("등록")) {
                System.out.print("명언 : ");
                sc.nextLine();
                System.out.print("작가 : ");
                sc.nextLine();
            } else if(command.equals("종료")) {
                break;
            }
        }
    }
}
