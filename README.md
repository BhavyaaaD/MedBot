# MedBot
MedBot is a comprehensive solution that provides personalized recommendations for nearby healthcare providers based on user descriptions of symptoms. It includes two main components: Medical Specialty Prediction and Chatbot Interface, integrated with the Practo API.

## Medical Speciality Predcition
This architecture comprises an embedding layer, a bidirectonal-LSTM layer with 32 units, and a dense layer with softmax activation for multi-class classification. We have added dropouts and recurrent droputs to prevent overfitting. The model is compiled with the Adam optimizer and categorical cross-entropy loss function.
