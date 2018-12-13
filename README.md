# weight-on-the-moon
just another repository about the moon
package com.company;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        //приветствие
        System.out.println("Здравствуйте , это программа поможет Вам узнать свой вес на Луне ");
        System.out.println();
        System.out.println("Начнем!");
        Scanner keyboard = new Scanner(System.in);
        //узнаем вес
        System.out.println();
        System.out.print("Чему равен Ваш вес на Земле,в кг? :  ");
        double weightPeopleEarth = keyboard.nextInt();
        //считаем вес
        double weightPeopleMoon = weightPeopleEarth*0.17;
        System.out.println();
        System.out.println("Ваш вес на Луне: " + weightPeopleMoon + "кг.");


        System.out.print("Гудбай !");
    }
}
