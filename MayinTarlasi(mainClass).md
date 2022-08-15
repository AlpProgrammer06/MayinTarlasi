```
package com.company;

import java.util.Scanner;

public class Main {


    public static void main(String[] args) {


        Scanner scanner = new Scanner(System.in);
        int row,col;

        System.out.println("Mayin Tarlasi Oyununa Hos Geldiniz : ");
        System.out.println("Lutfen oynamak istediginiz boyutlari giriniz: ");
        System.out.print("Satir Sayisi : ");
       row=scanner.nextInt();
        System.out.print("Sutun Sayisi : ");
        col=scanner.nextInt();

        MayinTarlasi mayin =new MayinTarlasi(row,col);
        mayin.run();

    }
}

```