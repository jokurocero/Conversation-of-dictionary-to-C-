# Conversation-of-dictionary-to-C-
https://youtu.be/DPgiYE35eVU?feature=shared
#include <iostream>
#include <string>
#include <map>

using namespace std;

int main() {
    map<string, string> DATA;
    DATA["ABACUS"] = "THE FIRST COMPUTER";
    DATA["NAPIER'S BONES"] = "INVENTED BY JOHN NAPIER";
    DATA["PASCALINE"] = "INVENTED BY BLAISE PASCAL";
    DATA["LEIBNIZ WHEEL"] = "INVENTED BY WILHELM LEIBNIZ";
    DATA["ANALYTICAL ENGINE"] = "INVENTED BY CHARLES BABBAGE";
    DATA["TABULATING MACHINE"] = "INVENTED BY HERMANN HOLLERITH";
    DATA["DIFFERENTIAL ANALYZER"] = "INTRODUCE IN 1930";
    DATA["MARK I"] = "INVENTED IN 1944 BY HOWARD AIKEN";
    DATA["FIRST GEN COMPUTER"] = "INVENTED IN 1940-1956";
    DATA["SECOND GEN COMPUTER"] = "INVENTED IN 1957-1963";
    DATA["THIRD GENERATION COMPUTER"] = "HAS INTEGRATED CIRCUITS";
    DATA["FOURTH GEN COMPUTER"] = "INVENTED IN YEAR 1971-1980";
    DATA["DIGITAL COMPUTERS"] = "ELECTRONIC DEVICES";
    DATA["ANALOG COMPUTER"] = "USED TO PROCESS DATA";

    string a;
    cout << "Say: ";
    cin >> a;

    if (DATA.count(a)) {
        cout << DATA[a] << endl;
    } else {
        cout << "Key not found." << endl;
    }

    return 0;
}
