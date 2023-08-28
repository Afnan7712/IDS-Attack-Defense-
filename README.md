# IDS-Attack-Defense-
This Project is regarding the adversarial attacks against IDS and the defense that is used to eliminate these attacks.

First of all, this project is built on CNN models: CNN-based IDS-1 and CN-based IDS-2. To build the first model with 'Pytorch', you can use the 'CNN_PyTorch_CNN-based IDS-1.ipynb' file. Then you can generate the adversarial attack (FGSM) in the second file named 'Generate.ipynb'. After that, you will need to build a GAN model with the CNN model to eliminate the FGSM attack by using the third file titled 'Train G_D_CNN-based IDS-1.ipynb'. 
The last two files were used to evaluate the CNN model when it used the GAN as a defender against the adversarial attack. Thus, the 'Test_Model_CNN-based IDS-1.ipynb' file tests the CNN-based IDS models against the FGSM attack, and the 'TEST_CNN-based IDS-1.ipynb' tests the CNN-based IDS-1 model against seven types of adversarial attacks.

Note: You can run the code by following this order: 
1. CNN_PyTorch_CNN-based IDS-1.ipynb. 
2. Generate.ipynb.
3. Train G_D_CNN-based IDS-1.ipynb.
4. Test_Model_CNN-based IDS-1.ipynb.
4. TEST_CNN-based IDS-1.ipynb.

Also, you can go through the same order for the CNN-based IDS-2 model.
