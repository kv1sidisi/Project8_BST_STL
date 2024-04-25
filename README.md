# Проект №8

### т.к 2 семестр еще не закончился, я не имею права загрузить реализацию проекта. Будет выгружен 01.09.2024

Три STL-совместимых контейнера для [BinarySearchTree](https://en.wikipedia.org/wiki/Binary_search_tree), реализующие различные [способы обхода дерева (in-, pre-, post-order)](https://en.wikipedia.org/wiki/Tree_traversal) через итератор.

## Свойства

Контейнер представляет из себя шаблон, праметрезируемый типом хранимых объетов, оператором сравнения и аллокатором, а так же удовлетворяет требованиям к stl - совместимым контейнерам:

  - [контейнера](https://en.cppreference.com/w/cpp/named_req/Container)
  - [ассоциативный контейнера](https://en.cppreference.com/w/cpp/named_req/AssociativeContainer)
  - [контейнера с обратным итератором](https://en.cppreference.com/w/cpp/named_req/ReversibleContainer)
  - [контейнера поддерживающие аллокатор](https://en.cppreference.com/w/cpp/named_req/AllocatorAwareContainer)
  - [oбладать двунаправленным итератом](https://en.cppreference.com/w/cpp/named_req/BidirectionalIterator)

Способ обхода дерева реализован через итератор, те оператор "++" должен приводить к перемещению итератора к следующему элементу в дереве, согласно правилу обхода.
