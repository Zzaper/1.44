package com.company;

import java.util.*;

public class rrr {
public static void mian(String[] args){
Scanner scr = new Scanner(System.in);

int bitcoins = Integer.parseInt(scr.nextLine());
double yuans = Double.parseDouble(scr.nextLine()):
double commission = Double.parseDouble(scr.nextLine());

if (bitcoins <= 20 && yuans <= 50000 && commission <= 5) {
double leva = bitcoins * 1168;
double dollar = yuans * 0.15;
double leva1 = dollar * 1.76;
double euro = (leva + leva1) / 1.95;

System.out.println(euro - (((commision /100)* euro))
}else
System.out.println("Wrong parameters");

  }
}
