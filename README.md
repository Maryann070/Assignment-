# Assignment-
Assignment 
#include <iostream>
using namespace std;

int main() {
    int arr[10]; // static array of size 10

    cout << "Enter 10 integers:" << endl;
    for (int i = 0; i < 10; ++i) {
        cin >> arr[i];
    }

    cout << "You entered: ";
    for (int i = 0; i < 10; ++i) {
        cout << arr[i] << " ";
    }
    cout << endl;
    return 0;
}
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int[] arr = new int[10]; // static array of size 10
        Scanner sc = new Scanner(System.in);

        System.out.println("Enter 10 integers:");
        for (int i = 0; i < 10; i++) {
            arr[i] = sc.nextInt();
        }

        System.out.print("You entered: ");
        for (int i = 0; i < 10; i++) {
            System.out.print(arr[i] + " ");
        }
        System.out.println();
        sc.close();
    }
}
