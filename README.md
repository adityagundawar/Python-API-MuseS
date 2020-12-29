# Python-API-MuseS

This API connects to the EEG sensor via a LSL Bridge which is created using application 'BlueMuse'.
In this API, the communication with the EEG sensor takes place on a daemon thread which lets it run independently and no asynchronous code is required on the client side.

References taken from -
https://github.com/alexandrebarachant/muse-lsl
