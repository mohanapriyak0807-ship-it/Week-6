# Week-6

import java.util.ArrayList;

class Week6 {
    public static void main(String[] args) {
        ArrayList<String> cart = new ArrayList<>();

        cart.add("Running Shoes");
        cart.add("Sports Shoes");
        cart.add("Leather Belt");

        System.out.println("===== YOUR CART =====");

        for (String item : cart) {
            System.out.println(item);
        }

        System.out.println("Total Products: " + cart.size());
    }
}
