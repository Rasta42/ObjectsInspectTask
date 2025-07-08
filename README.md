Папка для преднастроенных объектов /Content/Prototype/Items

String table для названий и описаний объектов /Content/Prototype/Items/ItemsStringTable

![Настройки объекта](https://github.com/user-attachments/assets/62e230f7-e2cc-4f07-9488-ba0c868f741d)

####Компонеты

Billboard Icon - маркер взаимодействия, необходимо расположить так, что бы она была заметна игроку на локации.

SceneComponent InitRotation - позволяет настроить начальнй поворот объекта при осмотре, красная стрелка указывает направление камеры осмотра.

Box - автоматически принимает размеры равные размерам баунда компонента, по этому доп настройка коллизий не требуется.

####Переменные

Text Name - имя указывается по ключу из Stringtable ItemsStringTable.

Text Description - имя указывается по ключу из Stringtable ItemsStringTable.

bool isCollectible - возможность подобрать объект. При подбирании объект скрывается со сцены и вызывает callback OnCollected.
