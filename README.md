# -22222 
a=[5, "Ирина", 6.8, "Спб", 54]
print(a)
for i in range (len(a)) :
    print(f"Тип переменной в списке: {type(a[i])}")

    my_list= input("Введите элементы списка:").split()
    my_list[:-1:2],my_list[1::2]=my_list[1::2],my_list[:-1:2]
    print(my_list)

    mon=input("Введите номер месяца")
    if mon=="12" or mon=="1" or mon=="2":
        print("зима")
    elif mon=="3" or mon=="4" or mon== "5":
            print("весна")
    elif mon=="6" or mon=="7" or mon=="8":
                print("лето")
    elif mon=="9" or mon=="10" or mon=="11":
                    print(осень)
    else:
        print("некорректный ввод числа")


        f= input("Введите значение").split()
        for i,el in enumerate(f,1):
            print(i, el[0:10])



            def change(a,z)
                max_z=max(a)
                if z>max_z
                    a.insert(0,z)
                elif z in a:
                    a.insert (a.index(z),z)
                else:
                    a.append(z)

            my_list2=[7,5,3,3,2]
            print(my_list2)
            change(my_list2,3)
            print(my_list2)
            change(my_list2,8)
            print(my_list2)
            change(my_list2,1)
            print(my_list2)
