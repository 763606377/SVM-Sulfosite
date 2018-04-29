https://github.com/HussamAlbarakati/SVM-Sulfosite

ReadMe:

//sequences data
1.file named 'Train_data.csv' has Train data for both positive and negative sequences. It has 900 positive data and it has 6856 negative data 
2.file named 'Test_data.csv' has test data for both positive and negative sequences. It has 145 positive data and it has 268 negative data

-------------------------------------------------------------------------------------------------------------------------------------------------------------

//Features data

3.file named 'Binary_train_420.csv' which has binary code (BE) of protein sequences include dummy residues(X) for train file. The feature length is 420
4.file named 'Binary_test_420.csv' which has binary code (BE) of protein sequences include dummy residues(X) for test file. The feature length is 420


5. file named 'AAindex_Train_280.csv' which has 14 physiochemical properties (AAindex) of protein sequences include dummy residues(X) for train file. The feature length is 280 
6.file named 'AAindex_test_280.csv' which has 14 physiochemical properties (AAindex) of protein sequences include dummy residues(X) for test file. The feature length is 280.

7. file named 'combine_train_1323_k_3.csv'which has k-space amino acid pairs (KSAAP) of protein sequences include dummy residues(X) for train file. The feature length is 1323.
8. file named 'combine_test_1323_k_3.csv'which has k-space amino acid pairs (KSAAP) of protein sequences include dummy residues(X) for test file. The feature length is 1323.

9.file named 'ACC_Train_20.csv' which has amino acid composition (AAC) of protein sequences did not include dummy residues(X) for train file. The feature length is 20.
10.file named 'ACC_test_20.csv' which has amino acid composition (AAC) of protein sequences did not include dummy residues(X) for test file. The feature length is 20.
 
11.file named 'HQ_train_160.csv' which has high-quality physiochemical indices (HQI) of protein sequences did not include dummy residues(X) for train file. The feature length is 160.
12.file named 'HQ_test_160.csv' which has high-quality physiochemical indices (HQI) of protein sequences did not include dummy residues(X) for test file. The 

13. compressed folder named "combine_files" has file named 'train_B_Aindex_kspace_ACC_HQ_2203.csv' we used with SVM to develop our method named'SVM-Sulfosite'which combined binary code(BE), 14 physiochemical properties(AAindex), k-space amino acid pairs(KSAAP), amino acid composition(AAC) and high-quality physiochemical indices(HQI) of protein sequences for train file. The feature length is 2203

14. compressed folder named"combine_files" has file named 'train_B_Aindex_kspace_ACC_HQ_2203.csv' we used with SVM to develop our method named'SVM-Sulfosite'which combined binary code(BE), 14 physiochemical properties(AAindex), k-space amino acid pairs(KSAAP), amino acid composition(AAC) and high-quality physiochemical indices(HQI) of protein sequences for test file. The feature length is 2203

-------------------------------------------------------------------------------------------------------------------------------------------------------------


 