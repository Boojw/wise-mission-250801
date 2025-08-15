package com.back;

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        System.out.println("== 명언 앱 ==");
        int no = 1;

        while(true) {
            System.out.print("명령) ");

                sc.nextLine();
                System.out.print("작가 : ");
                sc.nextLine();
                System.out.println("1번 명언이 등록되었습니다.");

                System.out.println("%d번 명언이 등록되었습니다.".formatted(no));
                no++;
            } else if(command.equals("종료")) {
                break;
            }
        }
    }
