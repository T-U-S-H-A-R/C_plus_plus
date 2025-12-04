#include <iostream>

int main()
 {
    int n;
    std::cout << "Enter number of elements: ";
    std::cin >> n;

    int a[n];
    std::cout << "Enter " << n << " elements:\n";
    for (int i = 0; i < n; i++)
        {
            std::cout<<"a["<<i<<"]";
            std::cin >> a[i];
    }
    for (int i = 0; i < n - 1; i++)
        {
            for (int j = 0; j < n - i - 1; j++)
            {
                if (a[j] < a[j + 1])
                {
                    int temp = a[j];
                    a[j] = a[j + 1];
                    a[j + 1] = temp;
            }
        }
    }

    std::cout << "Sorted array:\n";
    for (int i = 0; i < n; i++)
        {
        std::cout << a[i] <<std::endl;
    }
    std::cout << std::endl;
    return 0;
}
