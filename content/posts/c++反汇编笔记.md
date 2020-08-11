---
title: 'C++反汇编笔记'
date: 2020-08-11T22:21:29+08:00
---

## 除法

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c9fe2f03-b66b-4d9b-ac6e-5e22af899687/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c9fe2f03-b66b-4d9b-ac6e-5e22af899687/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a1c41509-809d-420c-afd4-15ab228acd44/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a1c41509-809d-420c-afd4-15ab228acd44/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/967e222e-4cf1-412c-89ee-324290453bcb/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/967e222e-4cf1-412c-89ee-324290453bcb/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7e916d89-6477-4150-bb6a-933c563f7a51/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7e916d89-6477-4150-bb6a-933c563f7a51/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/04a987f3-1fc4-4148-9ab6-066cf081120b/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/04a987f3-1fc4-4148-9ab6-066cf081120b/Untitled.png)

---

## 溢出

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7363fa07-1edc-4269-838f-77461054db8e/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7363fa07-1edc-4269-838f-77461054db8e/Untitled.png)

---

## 跳转

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e26a0bbf-03f8-40c3-a831-adb148459405/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e26a0bbf-03f8-40c3-a831-adb148459405/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a5c08998-06fa-4137-89ca-1766e53ddbc3/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a5c08998-06fa-4137-89ca-1766e53ddbc3/Untitled.png)

---

## 三目运算符

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9ca14001-d8f1-42e9-aa1c-22905e1ca28d/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9ca14001-d8f1-42e9-aa1c-22905e1ca28d/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9ed6d765-0d31-453e-b9f6-20628d91bdee/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9ed6d765-0d31-453e-b9f6-20628d91bdee/Untitled.png)

## 位运算

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1e222bf4-4958-4d70-a5c8-772b526fbd27/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1e222bf4-4958-4d70-a5c8-772b526fbd27/Untitled.png)

## 编译器优化

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b09a8dd1-6325-4f0d-b6d1-1889cc4bc357/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b09a8dd1-6325-4f0d-b6d1-1889cc4bc357/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0f88492b-7391-4bfa-b115-8010a90ee18d/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0f88492b-7391-4bfa-b115-8010a90ee18d/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a969d086-1def-4c7d-babb-3a41e9eb5000/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a969d086-1def-4c7d-babb-3a41e9eb5000/Untitled.png)

C/C++语言中逻辑右移和算数右移共享同一个运算符<<。编译器决定使用逻辑右移还是算数右移，根据的是运算数的类型。如果运算数类型是 unsigned 则采用逻辑右移，而 signed 则采用算数右移。对于 signed 类型的数据，如果需要使用算数右移，或者 unsigned 类型的数据需要使用逻辑右移，都需要进行类型转换。

算数右移，补符号位；逻辑右移，补 0

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/51f90281-76cb-4ae5-8acf-66cac5f11775/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/51f90281-76cb-4ae5-8acf-66cac5f11775/Untitled.png)

## 流程控制

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9adb8ddc-b4e9-46c1-93ac-02f421ecb436/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9adb8ddc-b4e9-46c1-93ac-02f421ecb436/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cf588f45-796d-45cb-9a3e-ea25dc603709/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cf588f45-796d-45cb-9a3e-ea25dc603709/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/aae9a472-f1f9-4e77-9c5f-88226383753b/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/aae9a472-f1f9-4e77-9c5f-88226383753b/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8c7d1417-ae5e-4c4f-8587-b63face54e6a/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8c7d1417-ae5e-4c4f-8587-b63face54e6a/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/81dcbeeb-3ed2-47bb-ae97-da0d89fe2abc/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/81dcbeeb-3ed2-47bb-ae97-da0d89fe2abc/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9062a757-9574-44e7-aa0b-073110bcff98/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9062a757-9574-44e7-aa0b-073110bcff98/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a7db38d4-c1d5-4cfc-b61b-8d424440f81a/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a7db38d4-c1d5-4cfc-b61b-8d424440f81a/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3cc86ce3-8af5-40bc-b071-3cd4d6029840/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3cc86ce3-8af5-40bc-b071-3cd4d6029840/Untitled.png)
