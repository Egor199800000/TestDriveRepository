# TestDriveRepository
package com.company;

public class TestArrays {

    public static void main(String[] args) {
        int[] index = new int[4];
        String[] island = new String[4];

        index[0] = 1;
        index[1] = 3;
        index[2] = 0;
        index[3] = 2;

        island[0] = "Бермуды";
        island[1] = "Фиджи";
        island[2] = "Азорские острова";
        island[3] = "Косумель";

        int y = 0;
        int ref;

        while (y < 4) {
            ref = index[y];
            System.out.println("Острова= ");
            System.out.println(island[ref]);
            y++;

        }


    }
}
