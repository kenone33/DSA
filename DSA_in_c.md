## 线性表

### ADT

```
ADT 线性表(List)
Data
    线性表的数据对象集合为{a1, a2, ......, an}，每个元素的类型均为 DataType。
    其中，除第一个元素a1外，每一个元素有且只有一个前驱元素，除了最后一个元素an外，每一个元素有且只有一个后继元素。
    数据元素之间的关系是一对一的关系。
Operation
    InitList(*L):初始化操作，建立一个空的线性表L。
    ListEmpty(L):若线性表为空，返回true,否则返回false。
    ClearList(*L):将线性表清空。
    GetElem(L, i, *e):将线性表L中的第i个元素值返回给e。
    LocateElem(L, e):在线性表L中查找与给定值e相等的元素。
    ListInsert(*L, i, e):在线性表L中的第i个位置插入新元素e。
    ListDelete(*L, i, e):删除线性表L中第i个位置元素，并用e返回其值。
    ListLength(L):返回线性表L的元素个数。
endADT
```
