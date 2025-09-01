<details>
  <summary><strong>GNN-Encoder Image Captioning Model | 2025.01 – 2025.04</strong></summary>
  <ul>
    <li>GitHub: <a href="https://github.com/hankunw/GNN-Encoder-Image-Captioning " target="_blank">Code</a></li>
    <li>Innovatively take usage of GNN Embedding layer in Image captioning encoder.</li>
    <li>Through comparative experiments, three models (as shown below) are trained and evaluated on Flicker8k dataset.</li>
    <ul>
      <li>Vision Transformer（ViT）Encoder Captioning Model</li>
      <li>Graph Convolutional Network（GCN）Encoder Captioning Model</li>
      <li>Graph Attention Network（GAT）Encoder Captioning Model</li>
    </ul>
    <li>Eventually test generalization ability of three models on COCO dataset.</li>
  </ul>
</details>

<br />

<details>
  <summary><strong>Text-guided Image Editing Model |2025.05 – Now</strong></summary>
  <ul>
    <li>GitHub: <a href="https://github.com/Not-Forrest/ece1508-text-guided-image-editing" target="_blank">Code</a></li>
    <li>Project Description: Developed a model pipeline to entangle information of text prompts with image and generate new image that includes both image and text information.</li>
    <li>Use VQ-VAE as backbone, add a mapper layer before the vector quantized layer, which takes text and image embedding and predict the embedding of target image. </li>
    <li>On the base of three loss components of VQ-VAE, we add a new loss term which we called mapper loss. It computes the mean square error between target image embedding and original image embedding. We train the model without mapper loss in first 30 epochs and separately train mapper with mapper loss.</li>
  </ul>
</details>

<br />

<details>
  <summary><strong>3D Viewer | 2024.01 – 2024.04</strong></summary>
  <ul>
    <li>GitHub: <a href="https://github.com/hankunw/3d-viewer " target="_blank">Code</a></li>
    <li>Developed an interactive 3D scene reconstruction viewer to simplify the 3D asset editing process and improve rendering efficiency.</li>
    <li>Main work includes:</li>
    <ul>
      <li><strong>Code Migration:</strong> Migrate the PyTorch-based 3D reconstruction technology (PAPR, Proximity Attention Point Rendering) from the original framework to Nerfstudio codebase.</li>
      <li><strong>Model Optimization:</strong> Identify rendering performance bottlenecks through benchmarking and design optimization solutions to improve real-time rendering speed.</li>
    </ul>
  </ul>
</details>

<br />

<details>
  <summary><strong>MyRuns | 2023.09 – 2023.12</strong></summary>
  <ul>
    <li>GitHub: <a href="https://github.com/hankunw/MyRuns " target="_blank">Code</a></li>
    <li>Developed an app that records users' motion mode, calories, and heart rate.</li>
    <li>Main work includes:</li>
    <ul>
      <li>Apply Google Map API in the application to record motion track of users.</li>
      <li>In automatic mode, the app automatically detects the user's activity type using Weka for automatic motion mode classification.</li>
      <li>User motion record can be recorded in the history tab.</li>
    </ul>
  </ul>
</details>

<br />

<details>
  <summary><strong>AI Chatbot Character | 2023.09 – 2023.12</strong></summary>
  <ul>
    <li>GitHub: <a href="https://github.com/hankunw/Character-Chatbot-Application " target="_blank">Code</a> | <a href="https://sites.google.com/view/362-group-22-project-webpage/home " target="_blank">Download</a></li>
    <li>Participated in Android App development. The app allows users to create their own chatbot character and engage in personalized conversations.</li>
    <li>Main features include:</li>
    <ul>
      <li><strong>Create Your AI:</strong> Users can build their unique AI character by providing brief descriptions (prompts).</li>
      <li><strong>Engage in Conversation:</strong> Have meaningful and personalized conversations with your AI character.</li>
      <li><strong>Prompt History:</strong> Access and modify your history of prompts to refine your character or steer the conversation in new directions.</li>
      <li><strong>Character Customization:</strong> During onboarding, design your AI character by submitting descriptive prompts. You can continuously evolve your AI companion by modifying these prompts.</li>
    </ul>
  </ul>
</details>

<br />

<details>
  <summary><strong>C-Shell Emulator | Jan 2022 – Apr 2022</strong></summary>
  <ul>
    <li>GitHub: <a href="https://github.com/hankunw/C-shell_simulator " target="_blank">Code</a></li>
    <li>Developed a Linux terminal emulator using the C programming language, closely simulating the behavior of a standard Linux command-line interface.</li>
    <li>Key features implemented include:</li>
    <ul>
      <li>Support for a wide range of common Linux shell commands (e.g., <code>ls</code>, <code>cd</code>, etc.)</li>
      <li>The ability for users to either enter commands interactively or provide them via a text file, which the emulator reads and executes line by line.</li>
      <li>Customizable user interface options allowing selection of different display themes and command output colors, including blue, red, and white color schemes.</li>
    </ul>
  </ul>
</details>

<br />

<details>
  <summary><strong>Video Super-Resolution Enhancement | Jan 2025 – Apr 2025</strong></summary>
  <ul>
    <li>GitHub: <a href="https://github.com/hankunw/Video_Super_Resolution " target="_blank">Code</a></li>
    <li>Participated in the development of a video resolution enhancement system for animated content. Utilized FFmpeg to parse videos, extract frames, and construct training datasets.</li>
    <li>Designed and evaluated three deep learning models for improving video frame resolution:</li>
    <ul>
      <li>An enhanced SRCNN-based model that first upscales the frame resolution and then refines the clarity, achieving improved super-resolution performance.</li>
      <li>A modified FSRCNN architecture incorporating skip connections to preserve fine details and improve feature propagation during super-resolution.</li>
      <li>Implemented, fine-tuned, and tested the RFDN (Residual Feature Distillation Network) model, optimizing its performance through extensive parameter adjustment and validation using metrics such as PSNR and SSIM.</li>
    </ul>
  </ul>
</details>

<br />

<details>
  <summary><strong>Toxic Comment Classification Model | Jan 2024 – Apr 2024</strong></summary>
  <ul>
    <li>GitHub: <a href="https://github.com/hankunw/Bert_Toxic_Comment_Classification " target="_blank">Code</a></li>
    <li>Developed a toxic comment classification system capable of identifying toxic or offensive language in user comments.</li>
    <li>Leveraged the BERT architecture via Hugging Face's model hub and fine-tuned it using the Tweets Toxic Comment dataset, achieving an accuracy of 93% on the test set.</li>
    <li>Implementation workflow included:</li>
    <ul>
      <li><strong>Data Preprocessing:</strong> Cleaned and prepared the dataset using Pandas and regular expressions (<code>re</code>) for text normalization. Tokenized the input data using the BERT tokenizer and built the corresponding vocabulary.</li>
      <li><strong>Model Deployment and Fine-tuning:</strong> Loaded and deployed a pre-trained BERT-based classification model from Hugging Face, and performed Supervised Fine-Tuning (SFT) on the annotated training dataset.</li>
      <li><strong>Model Evaluation:</strong> Evaluated model performance using accuracy and AUC (Area Under the Curve) metrics on the test dataset, ensuring robustness and generalization in detecting various forms of toxic language.</li>
    </ul>
  </ul>
</details>
