# Diagramming tools for UML

Sites : https://www.planttext.com/

## CNN
```
Input_Image->Convolutional_Layers:Feature_Extraction 
Convolutional_Layers->Pooling_Layers:Feature_Reduction 
Pooling_Layers->Fully_Connected_Layers:Representation_Learning 
Fully_Connected_Layers->Output:Class_Prediction
```

## RNN
```
@startuml

skin rose

Input_Sequence->Recurrent_Layer:Sequential_Feature_Extraction 
Recurrent_Layer->Output_Sequence:Contextual_Encoding 
Output_Sequence->Classification_Layer:Representation_Learning 
Classification_Layer->Output:Sentiment_Prediction

@enduml
```

## Transformer
```
@startuml

skin rose

Input_Sequence->Self-Attention_Mechanism:Contextual_Encoding 
Self-Attention_Mechanism->Feedforward_Neural_Networks:Feature_Transformation 
Feedforward_Neural_Networks->Output_Sequence:Representation_Learning 
Output_Sequence->Language_Model

@enduml
```


## GAN
```
@startuml

skin rose

Random_Noise->Generator_Network:Synthetic_Image_Generation 
Generator_Network->Generated_Image:Image_Refinement 
Generated_Image->Discriminator_Network:Adversarial_Training 
Discriminator_Network->Probability:Real/Fake

@enduml
```


## Autoencoder

```
Input_Image->Encoder_Network:Feature_Encoding 
Encoder_Network->Latent_Representation:Feature_Compression 
Latent_Representation->Decoder_Network:Feature_Decoding 
Decoder_Network->Reconstructed_Image

```

## Reinforcement 

```
Environment(Game)<-Agent:Action 
Agent->Action:Policy_Selection 
Action->Reward:Environment_Interactions 
Reward->Feedback(State,Reward)

```
