# Streams


# Spring
## Scope

The Spring Framework supports the following five scopes, three of which are available only if you use a web-aware ApplicationContext.

|scope | defination|
|--|--|
|**singleton**|The Spring Framework supports the following five scopes, three of which are available only if you use a web-aware ApplicationContext.|
|**prototype**|This scopes a single bean definition to have any number of object instances.|
|**request**|This scopes a bean definition to an HTTP request. Only valid in the context of a web-aware Spring ApplicationContext.|
|**session**|This scopes a bean definition to an HTTP session. Only valid in the context of a web-aware Spring ApplicationContext.|
|**global-session**|This scopes a bean definition to a global HTTP session. Only valid in the context of a web-aware Spring ApplicationContext.|



# Abstract Class vs. Interface
- Bir sınıf birden fazla interface’i inherit olarak alabilir ama bir sınıfa bir tane abstract class inherit alınabilir.
- Interface içerisinde boş metodlar tanımlanabilir ama abstract class’larda hem boş metodlar tanımlanabilir hemde içi dolu metodlar tanımlabilir.
- Abstract classları kullanmak hız açısından avantaj sağlar.
-  Interface de yeni bir metod yazdığımız zaman bu interfaceden implement ettiğimiz tüm classlarda bu metodun içini tek tek doldurmak gerekiyor ancak abstract classlarda durum farklıdır burada bir metod tanımlayıp içini doldurduğumuzda abstract sınıfımızdan türetilmiş bütün sınıflar bu özelliği kazanmış olur.
- Interfaceler çoklu kalıtımı sağlamaya yardımcı abstract classlar ise çoklu kalıtımı desteklemez.
-  Interface içerisindeki tüm nesnelerin “public” olması gerekirken Abstract classlarda tüm öğelerin “public” olması zorunlu değildir.
-  Interface yapıcı metodlar(constructor) içermez. Abstract class yapıcı metodlar içerebilir.
- Interface metodlar static olamaz. Abstract class soyut olmayan metodlar static olarak tanımlanabilir.