#include <iostream>
#include <cstdlib>
#include <string>
using namespace std;



int main(int argc, char* argv[])
{
	class human {
	public:
		
		int age, weight,height;
		string effect, name;
	};
	setlocale(LC_ALL, "rus");
	human men;
	cout << "Введите Ваше Имя: " << endl;
	cin >> men.name;
	cout << "Введите Ваш Вес: " << endl;
	cin >> men.weight;
	cout << "Введите Ваш Возраст: " << endl;
	cin >> men.age;
	cout << "Введите Ваш Рост(см): " << endl;
	cin >> men.height;
	cout << "Ваше имя- " << men.name << "\nВаш Вес- " << men.weight << "\nВаш Возраст- " << men.age << "\nВаш Рост- " << men.height << endl;
	if (men.weight == 48)
		cout << "Ваша Весовая Категория = Первый Наилегчайший Вес" << endl;
	else if (men.weight <= 51)
		cout << "Ваша Весовая Категория = Наилегчайший Вес" << endl;
	else if (men.weight <= 54)
		cout << "Ваша Весовая Категория = Легчайший Вес" << endl;
	else if (men.weight <= 57)
		cout << "Ваша Весовая Категория = Полулегкий Вес" << endl;
	else if (men.weight <= 60)
		cout << "Ваша Весовая Категория = Легкий Вес" << endl;
	else if (men.weight <= 64)
		cout << "Ваша Весовая Категория = Первый Полусредний Вес" << endl;
	else if (men.weight <= 69)
		cout << "Ваша Весовая Категория = Полусредний Вес" << endl;
	else if (men.weight <= 75)
		cout << "Ваша Весовая Категория = Средний Вес" << endl;
	else if (men.weight <= 81)
		cout << "Ваша Весовая Категория = Полутяжелый Вес" << endl;
	else if (men.weight == 91)
		cout << "Ваша Весовая Категория = Первый Тяжелый Вес" << endl;
	else if (men.weight << 91)
		cout << "Ваша Весовая Категория = Супертяжелый Вес" << endl;
	else
		cout << "Ошибка" << endl;
	system("pause");
	return 0;
}
