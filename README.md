# python_java_grammar

https://wikidocs.net/book/31

## 3. 자료형
### 1. 숫자
```oct(19)``` // ```int a  = 023```
```hex(12)``` // ```int a  =0xC```

```a.index(b)``` // ```a.indexOf(b)```
```b in a``` // ```a.contains(b)```
```a[1]``` // ```a.charAt(b)```
### 4. 문자열
```a = a.replace(b,c)```//	```a = a.replaceAll(b,c)```
```a[b:c]``` // ```a.substring(a,b+1)```
```a.upper()``` // ```a.toUpperCase()```
```a.split(b)``` // ```a.split(b)```
### 7. 리스트
```python
# python 리스트 생성
a = []
```
```java
// java 리스트 생성
import java.util.ArrayList;
ArrayList a = new ArrayList();
```
```lst.append(a)``` // ```lst.add(a)```
```lst[idx]``` // ```lst.get(idx)```
```len(lst)``` // ```lst.size()```
```b in lst``` // ```lst.contains(b)```
```del lst[idx]``` // ```lst.remove(idx)```
``` "sep".join(lst)```// ```String.join(sep,lst)```
```python
# python 리스트 정렬
a= [2,3,1]
a.sort()
a.sort(reverse = True)
```
```java
// java 리스트 정렬

import java.util.ArrayList;
import java.util.Comparator;
ArrayList a = new ArrayList();
a.add(2);
a.add(3);
a.add(1);
a.sort(Comparator.naturalOrder());
a.sort(Comparator.reverseOrder());
```


### 9. 맵
`dict` // `hashmap`
`dct = {}` // `HashMap<String, String> map = new HashMap<>();`
`dct[key] = value` // `map.put(key,value)`
`dct[key]` // `map.get(key)`
`if key in dct.keys()` // `map.containsKey(key)`
`len(dct)` // `map.size()`
`del dct[key]` // `map.remove(key)`
`list(dct.keys())` // `List<String> keyList = new ArrayList<>(map.keySet());`

### 10. 집합


## 4. 제어문

## 5. 객체지향 프로그래밍

## 6. 입출력


## 기타
### GCD
```python
#파이썬
def GCD(x,y):
    while y:
        x,y = y,x%y
    return y
```
```java
//자바
    public int GCD(int n, int m){ 
        int tmp;        
        while (m != 0){
            tmp = n;
            n = m;
            m = tmp%m;
        }
        return n;
    }
```
