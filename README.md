# The-Recipe-Library-of-Babel
An android exclusive application that generates creative cooking recipies. Perfect for those who want to relase their creativity.

### Extension to CNECCC-CSY/The Recipe Library of Babel

This respiratory will experience updates on February.

Test Version 0.90.00
Update logs:
1. The developing tool for the server will be changed to python if active. The client development tool will be changed to JavaScript. The original developing tool, App Inventor, will be discontinued.
2. New changes will be adopted into the generation processes including deep learning. The random generation will be replaced by a new generation method that will be open-sourced soon.
3. User interface will be changed, the guide will be less confusing(hopefully).

[Beta] Insights on deep learning of recipes:
Modified on the python server(with open sourced code).
Adopted Pytorch and numpy libraries.
Deep learning technique: the word to vector method will be adopted to generate continuous and relate reletivitity from cooking methods and ingredients.
Source: Wikipedia https://share.google/J4uLfFPSuw4wTw0Xa
The model pre-training+ fine tuning will be adopted to minimise user wait time and to boost the recommendation quality for the user. The server will execute training programs first, the the user can define their preferences.
Technical details: 
See the datasheet below.
1. Data classes includes regional datum, regional and universal ingredients, and universal procedures.
2. Weightings and procedures are considered very important to relating the commons of the ingredients and procedures. The ingredients are contained in the list  UNIVERSAL_INGREDIANTS and the procedures are contained in the list UNIVERSAL_PROCEDURES. The training is conducted in the class w2vtraining(list). The generation method is in generatedish(region, vec)
3. Communication between server and client are tunnelled by ngrok, a tunnelling service for python.
4. Please expect everything to change during Beta tests. The datasheet will be updating as versions progresses. Please report any bugs or security vulnerability in Github or get a ticket.

# CISCLAIMER
THE RECIPIES GENERATED ARE MEANT TO BE A JOKE. DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! DO NOT TRY THEM! I WILL NOT TAKE UP ANY RESPONSIBILITY IF ANYTHING GOES WRONG!

# Version 0.69.69
Added generator and tutorial screen.


Warning: This is still in testing! Please report any issues and bugs!
