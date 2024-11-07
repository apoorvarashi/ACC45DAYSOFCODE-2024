
#include <iostream>
#include <string>

int main() {
    // Declare and initialize a string
    std::string str = "Hello, World!";

    // Output the string
    std::cout << str << std::endl;

    // Input a string
    std::string input;
    std::cout << "Enter a string: ";
    std::getline(std::cin, input);

    // Concatenate strings
    std::string concatenated = str + " " + input;
    std::cout << concatenated << std::endl;

    // Find the length of a string
    int length = str.length();
    std::cout << "Length of '" << str << "': " << length << std::endl;

    // Access individual characters
    char firstChar = str[0];
    std::cout << "First character: " << firstChar << std::endl;

    // Modify a string
    str += " Modified";
    std::cout << str << std::endl;

    return 0;
}
