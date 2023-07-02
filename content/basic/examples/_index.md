---
date: "2017-04-24T18:36:24+02:00"
description: ""
hide:
title: 文档示例
weight: 4
---

>A bunch of Shortcodes are available with this theme :

### 警报提示

{{% alert primary %}}**this** is an primary{{% /alert %}}
{{% alert theme="info"%}}**this** is an info{{% /alert %}}
{{% alert theme="success" %}}**Yeahhh !** is a success{{% /alert %}}
{{% alert theme="warning" %}}**Be carefull** is a warning{{% /alert %}}
{{% alert danger %}}**Beware !** is a danger{{% /alert %}}
{{% alert dark %}}**Dark !** is a dark{{% /alert %}}
{{% alert light %}}**oooh !** is a light{{% /alert %}}
{{% alert secondary %}}**Wait !** is a secondary{{% /alert %}}

### 勋章标记

{{% badge %}}primary _(default)_{{% /badge %}}
{{% badge warning %}}In progress{{% /badge %}}
{{% badge secondary %}}docport{{% /badge %}}
{{% badge success %}}beta{{% /badge %}}
{{% badge danger %}}danger{{% /badge %}}
{{% badge warning %}}warning{{% /badge %}}
{{% badge info %}}info{{% /badge %}}
{{% badge light %}}light{{% /badge %}}
{{% badge dark %}}dark{{% /badge %}}

### 按钮

{{<button href="https://google.com" >}} go to google {{< /button >}}
{{<button href="https://google.com" theme="success">}} Success {{< /button >}}
{{<button href="https://google.com" theme="info">}} Info {{< /button >}}
{{<button href="https://google.com" theme="warning">}} Warning {{< /button >}}
{{<button href="https://google.com" theme="danger">}} Danger ! {{< /button >}}

{{<button href="https://google.com" theme="dark">}} Dark ! {{< /button >}}
{{<button href="https://google.com" theme="light">}} Light ! {{< /button >}}

### 栏位

5465465

### 摘要

{{%excerpt%}}
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation **ullamco** laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in _reprehenderit in voluptate_
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
{{% /excerpt%}}

### 可收缩的

{{%expand 打开看看呢%}}Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.{{%/expand%}}

### 通知

{{% notice success %}}Lorem ipsum dolor sit amet, consectetur.{{% /notice %}}
{{% notice %}}**Lorem !**\
 ipsum dolor sit amet, consectetur.{{% /notice %}}
{{% notice warning %}}**Lorem** ipsum dolor sit amet, consectetur{{% /notice %}}
{{% notice danger Attention %}}ipsum dolor sit amet{{% /notice %}}

### 面板

{{% panel theme="success" header="Success theme" %}}this is a panel text{{% /panel %}}
{{% panel theme="default" header="default theme" %}}this is a panel text{{% /panel %}}
{{% panel theme="primary" header="primary theme" %}}this is a panel text{{% /panel %}}
{{% panel theme="info" header="info theme" %}}this is a panel text{{% /panel %}}
{{% panel theme="warning" header="warning theme" %}}this is a panel text{{% /panel %}}
{{% panel theme="danger" header="danger theme" %}}this is a panel text{{% /panel %}}

### 标签页

{{< tabs >}}
{{% tab "PHP" %}} 

This is how we do a Hello world with php 

```php
	<?php 
	Print "Hello, World!";
	?>
```

{{%notice%}}php runtime needed to run{{%/notice%}}

{{% /tab %}}
{{< tab "Golang" >}} 

This is how we do a Hello world with go

```go
	package main
	import "fmt"
	func main() {
	    fmt.Println("hello world")
	}	
```

{{%notice%}}go needed to compile{{%/notice%}}


{{< /tab >}}
{{< tab "Java" >}} 

This is how we do a Hello world with java

```java
	class HelloWorld {
	    public static void main(String[] args) {
	        System.out.println("Hello, World!"); 
	    }
	}
```
{{%notice%}}java devkit needed to compile\
java runtime needed to run{{%/notice%}}

{{< /tab >}}
{{< /tabs >}}