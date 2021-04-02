# KCNJ5 mutation 相關筆記



## 2021-03-31 
### 初步清理資料
- 扣除'ID','Name','CaseID','p_testdate','p_birthdate','laparoscopic_Date'，以及兩個Y變項(KCNJ5變異)，'Operation_details'都是文字描述，先忽略。
- 最齊的欄位有：62個：'p_diagnosis3_Control', 'p_diagnosis4_Other', 'p_aldactone', 'HD_ACEI_pre', 'HD_a_blocker_pre', 'HD_b_blocker_pre', 'HD_ARB_pre', 'HD_CCB_pre', 'HD_Aldactone_pre', 'HD_aldactonDose_pre', 'HD_Aspirin_pre', 'HD_Vasodilator_pre', 'HD_DRIAliskiren_pre', 'HD_Diuretics_pre', 'HD_Other', 'LMA_Bloodfat', 'Smoking', 'AF', 'MI', 'CHF', 'COPD', 'HBV', 'HCV', 'LiverCirrhosis', 'ChronicGlomerulonephritis', 'Hyperthyroidism', 'Hypothyroidism', 'LVH', 'Gestationalhypertension', 'CT_check', 'CT_position', 'CT_Unilateral', 'NP59_check', 'NP59_position', 'MRI_checking', 'MRI_position', 'AVS_check', 'AVS_position', 'SaltLoadingTest_check', 'CaptoprilTest_check', 'outcome_12M', 'OP_text', 'OP', 'p_diagnosis1_APA', 'p_diagnosis2_BAH', 'p_sex', 'HTN_drug', 'HT', 'DM', 'Hyperlipidemia', 'Hypokalemia', 'CAD', 'CVA', 'RenalStone', 'K', 'KCNJ5_type_New', 'KCNJ5_Mutation_Bin_New', 'Bi_Unilateral', 'G151RKCNJ5', 'G151R_Type1', 'G151R_Type2', 'L168R'

- 其中有5個欄位的數值所有病人都一樣，確認暫不納入：'HD_DRIAliskiren_pre', 'MI', 'COPD', 'ChronicGlomerulonephritis', 'CT_check'

- 加上2個運算後的欄位：
   -'p_testdate-p'-'birthdate': 年齡
   -'laparoscopic_Date'-'birthdate':開刀年齡


- 缺少的資料當作沒有進行該檢查，需要把缺直都補上。


## 2021-03-30
- 確認資料，檔案版本為：KCNJ5_Dataset_Clean_20210331_check KCNJ5及驛馬簿.xlsx
- 資料版本為第四個頁籤，「整理後的檔案(清空無數值的欄位及無法辦識）」
- 共計328筆資料