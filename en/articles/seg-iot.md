---
area: articles
ref: seg-iot
title: Security on Embedded Systems and Internet of Things
lang: en
comments: true
---

<div class="alert">Warning! This is an working in progress article and its content may be incomplete and inconsistent.</div>

<img src="/img/iot.jpg" style="float: right;" width="400px" />

## Embedded system

**Embedded systems** are electronic and software systems that perform specific tasks, which make they different from general propose computers like smartphones, notebooks, desktops e servers. Every day, we make use of those devices without noticing, they are everywhere and doing almost everything. There are embedded systems in cars, TV, decoders, routers, switches, printers, radios, phones, etc.

## Internet of Things 

**Internet of Things** (**IoT**) is a network of embedded systems where each system is able to interoperate with Internet infrastructure. Such capacity brings integration opportunities between computer systems and the real world.

## Security challenges

The security challenges of embedded systems and of the IoT are similar to the conventional computers. Almost all attack technique used on conventional computers could be used to disrupt embedded systems. However, some embedded systems limitations make harder, or even unfeasible, the use of some common security controls.

As maiores dificuldade enfrentadas na implantação de mecanismos de segurança em sistemas embarcados e na Internet das Coisas são as limitações de memória, de armazenamento e de processamento que estes dispositivos possuem. Alguns controles de segurança utilizados em computadores convencionais, tais como antivírus, IDS, e até mesmo alguns mecanismos de firewall e de criptografia mais complexos, exigem muitos recursos de memória, processamento e armazenamento que normalmente não estão disponíveis em sistemas embarcados, pois seus hardwares normalmente são muito limitados. Outra limitação é a interface entre o sistema e seus os usuários, essa interface (quando existe) é normalmente muito limitada o que dificulta bastante a implementação de controles de segurança que exijam interações com o usuário. Um exemplo disso é o processo de atualização de sistemas e instalação de patches de segurança.
