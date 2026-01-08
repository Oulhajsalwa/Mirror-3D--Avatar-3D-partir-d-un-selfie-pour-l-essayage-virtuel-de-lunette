# Mirror-3D--Avatar-3D-partir-d-un-selfie-pour-l-essayage-virtuel-de-lunette


L'idée : Transformer une simple photo en avatar 3D réaliste



Théorie & Framework :
<img width="1193" height="379" alt="image" src="https://github.com/user-attachments/assets/1c70dab4-5469-400b-a798-3faf63818820" />
ID-Sculpt transforme une photo de portrait en modèle 3D en trois étapes séquentielles :

Génération de la géométrie Le système commence par créer la forme 3D de base . Cette étape utilise DMTET pour optimiser la géométrie 3D à partir de l'image portrait.

Génération de texture Ensuite, le système ajoute les textures sur la géométrie. Il projette l'image de référence sur le maillage 3D et remplit les zones non visibles avec de l'inpainting par diffusion.

Transfert de style (optionnel) Enfin, le système peut appliquer des modifications artistiques tout en préservant l'identité du visage.


Avancement:
<img width="921" height="530" alt="image" src="https://github.com/user-attachments/assets/c7ae60e4-4c21-477a-88b7-7ab24ed7bc19" />


Demo:


