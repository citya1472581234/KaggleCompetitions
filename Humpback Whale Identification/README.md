# Humpback Whale Identification

My solution was mostly based on this version of martinpiotte amazing work in the previous whale competition. I noticed many comments mentioning the variability of results obtained from Siamese networks, which I thought might be advantageous.

I made no modifications to Martin's network, training it  for 200 epochs. At that point it would consistently get between 0.86-0.89 on lb.Then I try spp(spatial pyramid pooling),l2,tail segmentation images decay and some iamge augmentation to get 0.9 on lb.

# Things that may work
* Ensembling (hard voting)
* classification network
* Weight decay
* Images larger than 384x384

# Conclusion
It's my first time to join kaggle competition,I'm happy with the final standings,I will participate more discussion in next competition.

