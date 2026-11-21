# Studi Komparatif Model Generatif (AE, Sparse AE, VAE, GAN, DCGAN, DDPM)

Repositori untuk **Tugas Take-Home Deep Learning Sesi 07: Generative Models**.

## Struktur Repositori

```text
deep-learning-ae-gan/
├── generative_models_study.ipynb
├── README.md
├── requirements.txt
└── results/
    ├── arch_1_autoencoders_mlp.png
    ├── arch_2_adversarial.png
    ├── arch_3_ddpm_unet.png
    ├── figure1_reconstruction_grid.png
    ├── figure2_generative_sampling.png
    ├── figure3_mlp_limitations.png
    ├── figure4_latent_interpolation.png
    ├── figure5_loss_and_ddpm_trajectory.png
    ├── metrics_summary.json
    └── training_histories.json
```

## Cara Menjalankan

1. Install dependency:
   ```bash
   pip install -r requirements.txt
   ```
2. Buka dan jalankan semua cell di `generative_models_study.ipynb` (menggunakan Jupyter Notebook, VS Code, atau Google Colab).
3. Seluruh metrik dan 5 figur wajib otomatis tersimpan di folder `results/`.
