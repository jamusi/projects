# Carrinho Mágico

## Introduction

Carrinho Mágico is an app that helps filling a shopping cart through voice commands, and is smart enough to know what the user wants.

## Description

Carrinho Mágico is an Android app which listens to your voice commands such as `preciso de manteiga vegetal` and it adds `manteiga vegetal` to your groceries list.
 
Since some information might be missing, e.g. quantity or brand, it uses your purchase history to automatically fill any missing information. It is also able to suggest products the user may want as well based on previous bundle buys (i.e. "I always buy tofu and Sriacha together").

We will be using Sonae's API and datasets for managing the shopping cart, train the machine learning and named entity recognition models. As such, the app will target the Continente market chain.

The app tries to engage the user to checkout the order: as soon as the user reaches the minimum ellegible total for free delivery (s)he'll be prompted to checkout; however, (s)he may order at all times.

Technologies we will use:
  * Java (Android)
  * Sketch
  * Python 
  * Freeling (Language Analysis)
  * MITIE (Named Entity Recognition)
  * Sonae's API/datasets
  * Google Speech Recognition

## Team

 * Alexandre Jesus https://pixels.camp/adbjesus
 * José Ribeiro https://pixels.camp/jlbribeiro
 * Tiago Silva https://pixels.camp/tiagomms
