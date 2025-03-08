# For-loop-and-nested-loop-group-10
1. #include <iostream>
using namespace std;

int main() {
    for (int i = 10; i >= 0; i--) {
        cout << i << endl;
    }
    return 0;
}

2. #include <iostream>
using namespace std;

int main() {
    for (int i = 10; i >= 0; i -= 2) {
        cout << i << endl;
    }
    return 0;
}

3. #include <iostream>
using namespace std;

int main() {
    int sum = 0;
    for (int i = 5; i <= 50; i += 3) {
        sum += i;
    }
    cout << "The sum of the series is: " << sum << endl;
    return 0;
}

4. #include <iostream>
using namespace std;

int main() {
    char input;
    for (int i = 0; i < 5; i++) {
        cout << "Enter a character: ";
        cin >> input;
        if (input == 'n') {
            cout << "Exiting the loop because 'n' was entered." << endl;
            break;
        }
    }
    return 0;
}

5. #include <iostream>
using namespace std;

int main() {
    for (int i = 0; i <= 5; i++) {
        cout << "Multiplication table of " << i << ":" << endl;
        for (int j = 0; j <= 10; j++) {
            cout << i << " * " << j << " = " << i * j << endl;
        }
        cout << endl;
    }
    return 0;
}
