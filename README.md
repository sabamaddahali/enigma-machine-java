##Enigma Machine (Java)

This project is a simple Java implementation of the Enigma Machine, created to understand how historical encryption worked and to practice object-oriented programming concepts.

The program simulates the main components of the Enigma machine, including rotors, a reflector, and character-by-character encryption.

##Project Overview

The Enigma Machine was a cipher device used during World War II to encrypt and decrypt messages.
This project recreates a simplified version of the Enigma machine in Java.

The program takes a user-entered message and encrypts it using multiple rotating rotors and a reflector.

##Features

Encrypts alphabetic characters (A–Z)

Preserves non-letter characters such as spaces and punctuation

Uses multiple Java classes to represent Enigma components

Demonstrates object-oriented programming principles

##File Structure

Main.java
Entry point of the program; handles user input and output

EnigmaMachine.java
Controls encryption flow and rotor stepping

Rotor.java
Represents a single Enigma rotor with forward and backward wiring

Reflector.java
Handles character reflection during encryption

##How It Works

1.The user enters a message
2.Each character passes through three rotors
3.The signal is reflected
4.The character passes back through the rotors in reverse order
5.Rotors rotate after each character is encrypted
6.The encrypted message is printed to the console

##Technologies Used
Java
Object-Oriented Programming
String manipulation
Console input/output

##Motivation

This project was built as a learning exercise to better understand historical cryptography and to practice designing programs using multiple classes in Java.

##Notes

This is a simplified simulation and does not fully replicate the historical Enigma machine.
The focus is on learning core concepts rather than exact historical accuracy.

##Author

Created by a student as a learning project in Java.
