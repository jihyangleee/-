# 2주차(스택/큐/링크드리스트)

## 01 스택과 큐를 구현하시오.
- 필수 구현 메서드는 다음과 같음
- Stack
  1. Enquqe: 스택 상단에 요소를 추가한다.
  2. Dequeue: 스택에서 맨 위 요소를 제거한다.
  3. Peek: 스택의 최상위 요소를 제거하지 않고 어떤 값인지 본다.
  4. IsEmpty: 스택이 비어있는지 확인한다.
 
- Queue
  1. Enquqe: 큐 뒤쪽에 요소를 추가한다.
  2. Dequeue: 큐에서 맨 앞의 요소를 제거한다.
  3. Peek: 큐의 맨 앞 요소를 제거하지 않고 어떤 값인지 본다.
  4. IsEmpty: 큐가 비어 있는지 확인한다.
 
``` python
stack =[]
stack.append(1) # Enqueue
stack.pop()
print(stack[-1]) # Peek
def isEmpty():
  return len(stack) ==0

## 02 linked list를 구현하시오.
- 필수 구현 메서드는 다음과 같음

  1. append: 리스트 가장 뒤에 값을 추가한다.
  2. prepend: 리스트 가장 앞에 값을 추가한다.
  3. delete: 원하는 값을 삭제한다.
  4. delete_first: 리스트 가장 앞에 있는 값을 삭제한다.
  5. display: 리스트를 출력한다.
