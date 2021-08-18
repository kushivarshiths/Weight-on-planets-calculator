#include <iostream>

int main() {
  double weight;

  std::cout << "What is his earth weight: ";
  std::cin >>weight;

  int planet_number;

  std::cout << "\nWhat number is the planet he want to fight: ";
  std::cin >>planet_number;
  
  switch(planet_number){


    case 1:
    std::cout << "\nTarget: " << 0.38*weight;
    break;
    case 2:
    std::cout << "\nTarget: " << 0.91*weight;
    break;
    case 3:
    std::cout << "\nTarget: " << 0.38*weight;
    break;
    case 4:
    std::cout << "\nTarget: " << 2.34*weight;
    break;
    case 5:
    std::cout << "\nTarget: " << 1.06*weight;
    break;
    case 6:
    std::cout << "\nTarget: " << 0.92*weight;
    break;
    case 7:
    std::cout << "\nTarget: " << 1.19*weight;
    break;
    default:
    std::cout << "\nWrong planet number";
    break;
 }

  
  }
  
  
  
  
  
  
  
  
  
