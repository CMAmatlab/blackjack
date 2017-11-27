# blackjack
matlab project
%Blackjack
%Mariah Smith 11/22/17

clear all; close all; clc
aceValue=menu('Choose value for ace','1','11'); %Choose the ace value
value=CardValue(hand,aceValue); %Find the value of the hand using the CardValue Function
%set up deck
deck=[
%make jack queen king equal to ten
%make ace equal to 1 or 11
%give players a starting $1000
%let players choose bet
%deal cards
%Check to see if there is a blackjack using IfBlackJack function
%let players hit or stand or double down or split
%if cards are the same value let them split
%make dealer deal to 16 and stand on 17
%person with value closest to 21 wins
%able to push
%money tracker (if player runs out of money they are kicked out)
%reshuffle deck
%repeat
