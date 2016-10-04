```c++
    int min = 101;
    int max = 0;
    for(int i = 0; i < 5; i++){
        int num = rand() % 101;
        printf("%d ", num);
        if(num < min)
            min = num;
        if(num > max)
            max = num;
    }
    printf("\n%d %d", min, max);
    return 0;
}
```
