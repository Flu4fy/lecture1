#include <iostream>
#include <string>

int calculateVariant2(std::string firstName, int numVariants) {
  int code = static_cast<int>(firstName[0]); // получения кода первой буквы имени
  return code % numVariants; // возвращение остатка от деления
}

int main() {
  std::string surname = "Иванов"; // можно заменить фамилию студента
  std::string firstName = "Иван"; // можно заменить имя студента
  int numVariants = 2; // можно заменить на число варинатов

  int variant1 = calculateVariant1(surname, numVariants);
  int variant2 = calculateVariant2(firstName, numVariants);

  std::cout << "Вариант 1: " << variant1 << std::endl;
  std::cout << "Вариант 2: " << variant2 << std::endl;

  return 0;
}
