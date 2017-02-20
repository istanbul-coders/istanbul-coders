    ---
layout: meeting
category: meetings
date: Thu, 23 Feb 2017 19:30:00 +0300
speaker: Hamza Ismail
speaker-homepage:
speaker-twitter: ham_ism
speaker-photo:
venue: Bahceşehir Üniversitesi Beşiktas Kampüs
title: Understanding Asynchronous Javascript
---

> Bize fikrinizi söyleyin. Sizi dinliyoruz: [https://talk.istanbulcoders.org/c/geri-bildirim](https://talk.istanbulcoders.org/c/geri-bildirim)

Merhaba Arkadaşlar,

Bu hafta Algiers (Cezayir)'den bir misafirimiz var. GDG Algiers ve Algiers nodeschool ekibinden Hamza Ismail bizlere "Understanding Asynchronous Javascript" başlıklı bir konuşma yapacak.

__Sunum dili İngilizce olacaktır__
Etkinlik B-401 nolu sınıfta __TSI 19:30'da__ gercekleştirilecektir.

**Konu:**

Most Real world Javascript apps are very asynchronous. as an example waiting for a user input or a file upload are unsurprisingly asynchronous processes, therefore learning how to compose and manage asynchronous code is a smart decision and can help us prevent our app complexity from exploding.

In this presentation I'll walk you through the basics of tackling asynchrony in Javascript,
starting by defining what it really is, clarifying the general misconception about it and concurrent code in general,
Then talking about the built-in way to achieve it in the name of Callbacks.

As you may already know callbacks are the humble solution to asynchrony in Javascript,
we will be giving some examples about this solution and mentioning some of its side effects like the notoriously known
"Callback hell" phenomenon.

To improve the first solution we will be considering promises, a new concept to the rescue.
promises are basically a time independent wrapper around a value or data coming in the future, to clear out this fancy description you can think of promises as in real life, for example
if you go to a bank and ask them to lend you some money and supposedly they say YES(they have made a promise), now you can go and make decisions based on that answer as if you already have the money, although it is not yours yet.
Well the same thing applies to promises, you can write code around values that don't exist yet and once they are available that code is executed using promises.

Another idea that it is not related to concurency but can be used with promises is generators, they are used to help us reason about our code as a synchronous blocks of code, cause we humans fundamentaly can't understand asynchronous code as we have to jump all around the code and see how things are being executed, instead we can use generators to make our code looks synchronous when it is not, so it is easy to reason and think about.

The third concept in the list is Observables, a new concept to solve the problem encountered when using promises with events and lots more.

The final concept that we will be talking about is CSP(Communicating Sequential Processes), a channel based model to solve concurency with a blocking techniques to send and recieve messages.


**Konuşmacı:**

Hamza Ismail (GDG Algiers)

**Yer:**

Bahceşehir Üniversitesi, Beşiktas B-401 Nolu sınıf

Etkinlik __TSI 19:30'da__ başlayacaktır

**Istanbul Coders Hakkında:**

- Bu ve daha sonraki toplantilardan haberdar olun: [http://istanbulcoders.org](http://istanbulcoders.org)
- Yeni platformumuza uye olun: [https://talk.istanbulcoders.org](https://talk.istanbulcoders.org)
- Twitter da bizi takip edin: [https://twitter.com/IstanbulCoders](https://twitter.com/IstanbulCoders)
- Meetup grubumuza katilin: [https://www.meetup.com/Istanbul-Hackers/](https://www.meetup.com/Istanbul-Hackers/)

----
