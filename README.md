# Language-Translation
Language Translation using Sequence to Sequence Recurrent Neural Network

Sequence to sequence neural network is used for machine translation. A sequence to sequence model is trained on a dataset 
of English and French sentences that can translate new sentences from English to French.

Neural Network is built following ways -
* Apply embedding to the input data for the encoder.
* Encode the input using your encoding_layer(rnn_inputs, rnn_size, num_layers, keep_prob).
* Process target data using your process_decoding_input(target_data, target_vocab_to_int, batch_size) function.
* Apply embedding to the target data for the decoder.
* Decode the encoded input using your decoding_layer(dec_embed_input, dec_embeddings, encoder_state, vocab_size, sequence_length, rnn_size, num_layers, target_vocab_to_int, keep_prob).
