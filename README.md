# Skimmed_CFG
A powerful anti-burn allowing much higher CFG scales for latent diffusion models (for ComfyUI)

CFG below at: 6/8/12/16/24/32, skimming scale at 6

![6_8_12_16_24_32](https://github.com/user-attachments/assets/6eb4beb6-0579-4f3e-a85e-e23b6472ebae)


Simply plug after the model loader:

![image](https://github.com/user-attachments/assets/b188947c-6226-42ff-b868-e6a44bbfe590)


Side-effects:

- better prompt adherence
- sharper images
- less mess / more randomness due to less conflicts in between the positive and negative predictions
- something something sometimes fused fingers with too low CFG scale or too low amount of steps.


Tips:

- The skimming scale is basically how much do you like them burned. 3 was the intended scale but suit to your needs.
- SDE samplers can still burn a little but much less
- A too low skimming scale may require to do more steps
- Recommanded skim: 2-3 for maximum antiburn, 5-7 for colorful/strong style.



# Pro tip:

[It would be actually nice to have some support!](https://www.patreon.com/extraltodeus)

Did you know that my first activity is to write creative model merging functions?

While the code is too much of a mess to be shared, I do expose and share my models. You can find them in this [gallery](https://github.com/Extraltodeus/shared_models_galleries)! 😁
