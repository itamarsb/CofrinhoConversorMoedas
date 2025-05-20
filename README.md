# CofrinhoConversorMoedas
Cofrinho conversor de moedas simples em Java

Atividade/Desafio do Curso de Engenharia de Computação - Programação Orientada à Objetos - Uninter

OBJETIVO

O trabalho consiste em implementar um pequeno sistema que emula um "Cofrinho de moedas" em Java. Foi desenvolvido um menu em que é oferecido ao usuário:
 Adicionar moedas de diferentes valores e países em seu cofrinho;
 Remover moedas específicas do cofrinho;
 Listar todas as moedas que estão dentro do cofrinho;
 Calcular quanto dinheiro existe no cofrinho convertido para a moeda Real brasileira;

O objetivo principal do trabalho foi avaliar o bom uso do conceito de herança e polimorfismo. O projeto possui uma classe Principal além das classes descritas no diagrama UML em anexo.

A classe Cofrinho deve possui como atributo uma coleção de Moedas, que por sua vez é uma classe mãe abstrata de outras classes específicas de Dolar, Euro, Real, etc... A coleção de Moedas é implementada utilizando um ArrayList.
