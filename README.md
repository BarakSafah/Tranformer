# Tranformer
## Hush, the seagulls are purring: On generating humorous captions from scene descriptions
The goal of this project is to finetune Seagull, a large language transformer model to generate humorous captions, given a scene and associated uncanny description. To this end, you will:

understand and process data as needed (tokenization, padding, truncation, etc.),
generate learnable latent representations for tokens (embeddings),
implement multi-head attention to capture "context" and feed-forward to enable pointwise transformations,
assemble a transformer layer using the implemented multi-head attention and feed-forward modules,
attach a language modeling head to the transformer, and
finetune your Seagull from a pretrained model, to generate humorous captions.
