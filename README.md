# ESP32 - Arduino Component

Utilização do Arduino component em conjunto com ESP-IDF

## Índice

## Introdução

Esse repositório será dedicado a quem deseja utilizar o arduino component([arduino-esp32](https://github.com/espressif/arduino-esp32)) em conjunto com o toolkit oficial do esp32 - ESP-IDF.

Isso irá fazer com que você não necessite utilizar a IDE do Arduino, assim tendo um controle mais delicado sobre o firmware e das diversas configurações referente ao ESP32.

**Obs:** Aqui detalharei o processo para ser aplicado em Ambiente Linux, mas com um pouco de esforço pode ser facilmente replicado em ambiente Windows.

## Preparando o ambiente

### Criando pasta base

```
cd
mkdir esp32
cd esp32
```

Essa pasta base pode ser criada em qualquer lugar, fica de sua preferência :)

## Download das dependências

### ESP-IDF

```
cd ~/esp32

```

### Xtensa
```
cd ~/esp32
```

### Arduino Component

```
cd ~/esp32
cp sdk/examples/get-started/blink ./blink
```

## Configurando o ambiente

### ESP-IDF

### Arduino component

## Blink

* Exemplo base

```c
```

* Exemplo com integração total

```c
```

## Referências

* [Xtensa](https://docs.espressif.com/projects/esp-idf/en/latest/get-started/linux-setup.html)
* [ESP-IDF](https://docs.espressif.com/projects/esp-idf/en/latest/get-started/#get-started-get-esp-idf)
* [Arduino component](https://github.com/espressif/arduino-esp32/blob/master/docs/esp-idf_component.md)