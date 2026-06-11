# Customer Data Processing with Java OOP

## English

This repository contains a Java project developed to process customer data using object-oriented programming principles and custom data structures.

The application reads customer records from an external text file, represents each customer with a dedicated class, and processes the data using structures such as a custom linked list and a two-dimensional array. The project focuses on organizing customer information, storing records in memory, and applying basic data processing operations through a structured Java application.

The project was built to practice how real input data can be converted into objects and managed through manually implemented data structures instead of relying only on built-in collections.

---

## Project Overview

The application is designed around customer records. Each customer is represented as an object, and the customer data is read from an external text file.

After reading the file, the program organizes the data using different structures:

* A custom customer data class
* A custom linked list structure
* A two-dimensional array structure

This structure makes it possible to compare how different data representations can be used to store, access, and process the same type of information.

---

## Main Components

### Customer Data Model

The project includes a customer data class that represents the information of a single customer.

This part focuses on object modeling. Instead of keeping customer information as raw text, the program converts the data into structured objects. This makes the code easier to manage, extend, and process.

---

### Custom Linked List

The project includes a manually implemented linked list structure for storing customer records.

This part demonstrates how nodes are connected, how customer objects can be stored inside a dynamic structure, and how data can be processed without depending only on Java’s built-in collection classes.

---

### Two-Dimensional Array Processing

The application also includes a two-dimensional array structure.

This part shows how customer-related data can be organized in a table-like format. Working with two-dimensional arrays helped me practice index-based data access and understand how structured data can be represented in rows and columns.

---

### File-Based Data Input

Customer data is read from an external text file.

This part of the project focuses on reading data from a file, separating raw input into meaningful parts, and converting it into usable objects inside the program.

---

## Features

* Reads customer data from an external text file
* Represents customer records using a custom class
* Stores and processes customer objects
* Implements a custom linked list structure
* Uses a two-dimensional array for structured data representation
* Applies object-oriented programming principles
* Separates data modeling, storage, and processing logic
* Runs as a Java console application

---

## Technologies Used

* Java
* NetBeans
* Object-Oriented Programming
* File I/O
* Custom Linked List
* Two-Dimensional Array
* Console Application Development

---

## What I Implemented and Learned

In this project, I practiced converting raw file input into structured Java objects and managing those objects using custom data structures.

By creating a customer data class, I worked on object modeling and encapsulating related information inside a single structure. This helped me understand how real-world data can be represented more cleanly through classes.

By implementing a linked list, I practiced the logic behind dynamic data structures, node connections, and manual record storage. This made the difference between fixed-size and dynamic data organization clearer.

By using a two-dimensional array, I practiced table-like data representation and index-based access. This helped me understand how data can be organized in rows and columns when a more structured layout is needed.

Main topics I practiced:

* Creating custom Java classes
* Reading data from external files
* Converting raw text data into objects
* Implementing a custom linked list
* Working with nodes and object references
* Using two-dimensional arrays
* Organizing code with object-oriented programming principles
* Building a Java console application with separated responsibilities

---

# Java OOP ile Müşteri Verisi İşleme

## Türkçe

Bu repository, müşteri verilerini nesne yönelimli programlama prensipleri ve özel veri yapıları kullanarak işleyen bir Java projesini içermektedir.

Uygulama, müşteri kayıtlarını harici bir metin dosyasından okur, her müşteriyi özel bir sınıf ile temsil eder ve verileri custom linked list ile iki boyutlu array gibi yapılar üzerinde işler. Proje; müşteri bilgilerini organize etme, kayıtları bellekte saklama ve temel veri işleme işlemlerini düzenli bir Java uygulaması üzerinden gerçekleştirme üzerine kuruludur.

Bu proje, gerçek veri girişinin nesnelere nasıl dönüştürülebileceğini ve bu nesnelerin yalnızca hazır collection yapılarıyla değil, manuel olarak implemente edilen veri yapılarıyla da nasıl yönetilebileceğini uygulamak için geliştirildi.

---

## Proje Özeti

Uygulama müşteri kayıtları üzerine kuruludur. Her müşteri bir nesne olarak temsil edilir ve müşteri verileri harici bir metin dosyasından okunur.

Dosya okunduktan sonra program verileri farklı yapılarla organize eder:

* Özel müşteri veri sınıfı
* Custom linked list yapısı
* İki boyutlu array yapısı

Bu yapı, aynı türdeki verinin farklı veri temsil biçimleriyle nasıl saklanabileceğini, erişilebileceğini ve işlenebileceğini göstermektedir.

---

## Ana Bileşenler

### Customer Data Model

Projede, tek bir müşteriye ait bilgileri temsil eden özel bir müşteri veri sınıfı bulunmaktadır.

Bu bölüm nesne modellemeye odaklanır. Müşteri bilgilerini ham metin olarak tutmak yerine, program bu verileri yapılandırılmış nesnelere dönüştürür. Bu yaklaşım kodun daha düzenli, yönetilebilir ve geliştirilebilir olmasını sağlar.

---

### Custom Linked List

Projede müşteri kayıtlarını saklamak için manuel olarak implemente edilmiş bir linked list yapısı bulunmaktadır.

Bu bölüm; node bağlantılarının nasıl kurulduğunu, müşteri nesnelerinin dinamik bir yapı içinde nasıl saklanabileceğini ve Java’nın hazır collection sınıflarına tamamen bağlı kalmadan veri yönetiminin nasıl yapılabileceğini gösterir.

---

### Two-Dimensional Array Processing

Uygulamada iki boyutlu array yapısı da kullanılmaktadır.

Bu bölüm, müşteriyle ilgili verilerin tablo benzeri bir formatta nasıl organize edilebileceğini gösterir. İki boyutlu array ile çalışmak, index tabanlı veri erişimini ve verinin satır-sütun mantığıyla nasıl temsil edilebileceğini uygulamamı sağladı.

---

### File-Based Data Input

Müşteri verileri harici bir metin dosyasından okunur.

Bu bölümde dosyadan veri okuma, ham girdiyi anlamlı parçalara ayırma ve program içinde kullanılabilir nesnelere dönüştürme işlemleri uygulanmıştır.

---

## Özellikler

* Harici metin dosyasından müşteri verisi okuma
* Müşteri kayıtlarını özel bir sınıf ile temsil etme
* Müşteri nesnelerini saklama ve işleme
* Custom linked list yapısı implemente etme
* Yapılandırılmış veri gösterimi için iki boyutlu array kullanma
* Nesne yönelimli programlama prensiplerini uygulama
* Veri modeli, veri saklama ve işlem mantığını ayırma
* Java konsol uygulaması olarak çalışma

---

## Kullanılan Teknolojiler

* Java
* NetBeans
* Nesne Yönelimli Programlama
* Dosya Okuma İşlemleri
* Custom Linked List
* İki Boyutlu Array
* Konsol Uygulaması Geliştirme

---

## Bu Projede Ne Uyguladım ve Ne Öğrendim?

Bu projede, harici dosyadan gelen ham veriyi Java nesnelerine dönüştürmeyi ve bu nesneleri özel veri yapılarıyla yönetmeyi uyguladım.

Customer data sınıfı oluşturarak nesne modelleme ve ilişkili bilgileri tek bir yapı altında toplama konusunda çalıştım. Bu, gerçek dünyadaki verilerin class yapılarıyla daha düzenli şekilde nasıl temsil edilebileceğini anlamamı sağladı.

Linked list implementasyonu ile dinamik veri yapılarının çalışma mantığını, node bağlantılarını ve manuel kayıt saklama yapısını uyguladım. Bu sayede sabit boyutlu veri organizasyonu ile dinamik veri organizasyonu arasındaki farkı daha net gördüm.

İki boyutlu array kullanarak tablo benzeri veri temsilini ve index tabanlı erişimi pratik ettim. Bu yapı, verinin satır-sütun mantığında düzenlenmesi gerektiğinde nasıl kullanılabileceğini anlamamı sağladı.

Bu projede pratik yaptığım ana konular:

* Java’da özel sınıf oluşturma
* Harici dosyadan veri okuma
* Ham metin verisini nesnelere dönüştürme
* Custom linked list implementasyonu
* Node ve object reference mantığıyla çalışma
* İki boyutlu array kullanımı
* Nesne yönelimli programlama prensipleriyle kod organize etme
* Sorumlulukları ayrılmış Java konsol uygulaması geliştirme
