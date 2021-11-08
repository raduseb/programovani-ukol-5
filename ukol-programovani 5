package net.sevecek.turtle;

import net.sevecek.turtle.engine.*;

public class HlavniProgram {

    Turtle zofka;

    public void main(String[] args) {


        zofka = new Turtle();

//         nakresliRovnoramennyTrojuhelnik(150,200);
//       nakresliTrojuhelnik(100);

//        zofka.move(100);
//        nakresliCtverec(200);
//        zofka.move(100);
//        nakresliObdelnik(300.5,150.5);
//          nakresliKolecko(50);

        nakresliMasinku();
        nakresliSnehulaka();
        nakresliZmrzlinu();

//        zofka.turnLeft(90);
//        zofka.penUp();
//        zofka.move(100);
//        zofka.penDown();
//
//
//
//
//


    }

    public void nakresliTrojuhelnik(double delkaStrany) {
        zofka.turnRight(90);
        for (int i = 0; i < 3; i++) {
            zofka.move(delkaStrany);
            zofka.turnRight(120);

        }
    }


    public void nakresliRovnoramennyTrojuhelnik(double x, double y) {
        zofka.turnRight(90);
        zofka.move(x);
        zofka.turnRight(90);
        zofka.move(x);
        zofka.turnRight(135);
        zofka.move(y);
    }


    public void nakresliZmrzlinu() {
        zofka.setLocation(50,400);
        nakresliTrojuhelnik(200);
        zofka.setLocation(138,480);
        nakresliKolecko(23);
        zofka.turnLeft(90);

    }

    public void nakresliSnehulaka() {
        zofka.setLocation(500,400);
        zofka.turnLeft(90);
        nakresliKolecko(30);
        zofka.setLocation(500,250);
        nakresliKolecko(20);
        zofka.setLocation(500,175);
        nakresliKolecko(10);
        zofka.setLocation(395,300);
        nakresliKolecko(5);
        zofka.setLocation(590,300);
        nakresliKolecko(5);
        zofka.turnRight(90);

    }

    public void nakresliMasinku() {
        zofka.setLocation(1100,450);
        nakresliObdelnik(300,150);
        zofka.turnLeft(90);
        nakresliObdelnik(300,150);
        zofka.turnLeft(90);
        nakresliKolecko(20);
        zofka.turnRight(90);
        zofka.move(80);
        nakresliKolecko(11);
        zofka.move(120);
        nakresliKolecko(11);
        zofka.move(100);
        zofka.turnRight(90);
        zofka.move(110);
        zofka.turnRight(90);
        nakresliRovnoramennyTrojuhelnik(150,210);
        zofka.turnLeft(45);

    }

    public void nakresliKolecko(double polomer) {
        for (double i = 0; i < 24; i++) {
            zofka.move(polomer);
            zofka.turnLeft(15);

        }

    }

    public void nakresliObdelnik(double a, double b) {
        for (double i = 0; i < 2; i++) {
            zofka.move(a);
            zofka.turnRight(90);
            zofka.move(b);
            zofka.turnRight(90);


        }
    }

    public void nakresliCtverec(double delkaStrany) {
        for (double i = 0; i < 4; i++) {
            zofka.move(delkaStrany);
            zofka.turnLeft(90);
//
//        }
//
//    }
        }


    }
}
