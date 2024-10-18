CREATE folder '1st' and copy the TELCO dataset
CREATE folder '2nd' and copy the ADULT dataset
CREATE folder '3rd' and copy the CREDITCARD dataset

First ->
    You have to run the "preprocess.ipnyb" file
        - For Dataset 1 (Telco)      - UNCOMMENT  "dataset_one()"    function
        - For Dataset 2 (Adult)      - UNCOMMENT  "dataset_two()"    function
        - For Dataset 3 (Creditcard) - UNCOMMENT  "dataset_three()"  function

    Then -> Run All

    This will create a "dataset.csv"
    ONLY for dataset 2 there will be a additional "dataset_test.csv"


Second -> 
    LOAD data:
        - dataset 2 -> UNCOMMENT 1 line under this comment
    
    SPLIT text:  
        - for dataset 1 and 3 -> UNCOMMENT 1 line under this comment 
        - for dataset 2       -> UNCOMMENT 2 lines under this comment 

        This methods will create proper train, validation and test set

    ATTRIBUTES:
        - for dataset 1 
            - learning rate = 1
            - num_iteration = 100

        - for dataset 2
            - learning rate = 1.5
            - num_iteration = 100

        - for dataset 3 
            - learning rate = 50
            - num_iteration = 100
    

    Then -> Run All