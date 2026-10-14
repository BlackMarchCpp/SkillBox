Задание 1. 
#include <iostream>

int main(){
    int ringNumber = 4;
    int racerOrder = 358;
    int engineBolid = 254; 
    int wheelsBolid = 93;
    int rudderBolid = 49;
    int windResistance = 21;
    int sediment = 17;
    int speedBolid = engineBolid + wheelsBolid + rudderBolid - (windResistance+sediment);
    std::cout <<"===========================================================\n";
    std::cout <<"Супер гонки.\n" "Круг "<<  ringNumber << "\n";
    std::cout <<"===========================================================\n";
    std::cout <<"Водитель: Шумахер" "(" << racerOrder << ")\n";
    std::cout <<"Скорость: " << speedBolid << "\n";
    std::cout <<"-----------------------------------------------------------\n";
    std::cout <<"Оснащение: \n";
    std::cout <<"Двигатель: +" <<engineBolid<< "\n"; 
    std::cout <<"Колеса: +" <<wheelsBolid<< "\n" "Руль: -" <<rudderBolid<< "\n"; 
    std::cout << "----------------------------------------------------------\n";
    std::cout <<"Действие плохой погоды.\n" "Ветер: -" <<windResistance<< "\n" "Дождь: -" <<sediment<< "\n";

}
