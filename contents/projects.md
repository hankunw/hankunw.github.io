GNN-Encoder Image Captioning Model | 2025.01 – 2025.04: [[Code]](https://github.com/hankunw/GNN-Encoder-Image-Captioning) \
Innovatively take usage of GNN Embedding layer in Image captioning encoder. Through comparative experiments, three models (as shown below) are trained and evaluated on Flicker8k dataset.
- Vision Transformer（ViT）Encoder Captioning Model
- Graph Convolutional Network（GCN）Encoder Captioning Model
- Graph Attention Network（GAT）Encoder Captioning Model
- Eventually test generalization ability of three models on COCO dataset


3d-viewer | 2024.01 – 2024.04: [[Code]](https://github.com/hankunw/3d-viewer) \
Developed an interactive 3D scene reconstruction viewer to simplify the 3D asset editing process and improve rendering efficiency. The main work includes: 
- Code Migration：Migrate the Pytorch-based 3D reconstruction technology (PAPR, Proximity Attention Point Rendering) from the original framework to Nerfstudio codebase. 
- Model Optimization：Identify rendering performance bottlenecks through benchmarking and design optimization solutions to improve real-time rendering speed


MyRuns | 2023.09 – 2023.12: [[Code]](https://github.com/hankunw/MyRuns) \
Developed an app that records users' motion mode, calories, and heart rate. The main work includes: 
- Apply Google Map Api in the application to record motion track of users. 
- In automatic mode, the app automatically detects the user's activity type. Using Weka to perform automatic motion mode classification. 
- User motion record can be recorded in the history tab 


AI Chatbot Character | 2023.09 – 2023.12: [[Code]](https://github.com/hankunw/Character-Chatbot-Application) [[Download]](https://sites.google.com/view/362-group-22-project-webpage/home) \
Participates in an Android App development. The app can let user create their own chatbot character and chat with the character by their preference. The main feature includes: 
- Create Your AI: Users can build their unique AI character by providing brief descriptions (prompts).
- Engage in Conversation: Have meaningful and personalized conversations with your AI character.
- Prompt History: Access and modify your history of prompts to refine your character or steer the conversation in new directions.
- Character Customization: During onboarding, design your singular AI character by submitting descriptive prompts. You can continuously evolve your AI companion by modifying these prompts.


C-Shell Emulator | Jan 2022 – Apr 2022: [[Code]](https://github.com/hankunw/C-shell_simulator)
Developed a Linux terminal emulator using the C programming language, closely simulating the behavior of a standard Linux command-line interface. Key features implemented include:
- Support for a wide range of common Linux shell commands (e.g., ls, cd, etc.)
- The ability for users to either enter commands interactively or provide them via a text file, which the emulator reads and executes line by line
- Customizable user interface options allowing selection of different display themes and command output colors, including blue, red, and white color schemes


Video Super-Resolution Enhancement | Jan 2025 – Apr 2025: [[Code]](https://github.com/hankunw/Video_Super_Resolution)
Participated in the development of a video resolution enhancement system for animated content. Utilized FFmpeg to parse videos, extract frames, and construct training datasets. Designed and evaluated three deep learning models for improving video frame resolution:
- An enhanced SRCNN-based model that first upscales the frame resolution and then refines the clarity, achieving improved super-resolution performance.
- A modified FSRCNN architecture incorporating skip connections to preserve fine details and improve feature propagation during super-resolution.
- Implemented, fine-tuned, and tested the RFDN (Residual Feature Distillation Network) model, optimizing its performance through extensive parameter adjustment and validation using metrics such as PSNR and SSIM.



Toxic Comment Classification Model | Jan 2024 – Apr 2024: [[Code]](https://github.com/hankunw/Bert_Toxic_Comment_Classification)
Developed a toxic comment classification system capable of identifying toxic or offensive language in user comments. Leveraged the BERT architecture via Hugging Face's model hub and fine-tuned it using the Tweets Toxic Comment dataset, achieving an accuracy of 93% on the test set. The implementation workflow included:
- Data Preprocessing: Cleaned and prepared the dataset using Pandas and regular expressions (re) for text normalization. Tokenized the input data using the BERT tokenizer and built the corresponding vocabulary.
- Model Deployment and Fine-tuning: Loaded and deployed a pre-trained BERT-based classification model from Hugging Face, and performed Supervised Fine-Tuning (SFT) on the annotated training dataset.
- Model Evaluation: Evaluated model performance using accuracy and AUC (Area Under the Curve) metrics on the test dataset, ensuring robustness and generalization in detecting various forms of toxic language.
