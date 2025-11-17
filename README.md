#include <stdio.h>
int main () {
    int patient,list;
    printf("Hospitalized Patients list\nIf you want me to display the list enter 1==\n");
    scanf("%d",&list);
    printf("***********************************");
    if(list==1){
        printf("\nPatient Hospitalized:\n 1.Rahul Jadhav\n 2.Shilpa Pawar\n 3.Akash Singh\n 4.Ravi Prasad\n\n ");
         printf("Enter Patients number:");
     
        scanf("%d",&patient);
                printf("==============================\n");
    }
    else{
        printf("\n");
    }
    
    
    switch(patient) {
        case 1:
        printf(" HOSPITALIZATION DATE:22/10/25 \n AGE: 26\n HEALTH ISSUE:Dengue\n ROOM NUMBER:004\n REFERRED DOCTOR:Dr.Ajay Shinde\n MEDICAL TESTS TO  BE DONE:Blood test ");
        break;
        case 2:
          printf(" HOSPITALIZATION DATE:11/10/25 \n AGE: 45\n HEALTH ISSUE:High Fever\n ROOM NUMBER:002\n REFERRED DOCTOR:Dr.Akshita Rathi\n MEDICAL TESTS TO  BE DONE:Blood test and urine test ");
        break;
        case 3:
         printf(" HOSPITALIZATION DATE:15/10/25 \n AGE:34\n HEALTH ISSUE:Stomach Pain\n ROOM NUMBER:005\n REFERRED DOCTOR:Dr.Sneha Kulkarni\n MEDICAL TESTS TO  BE DONE:Sonography ");
         break;
         case 4:
         printf(" HOSPITALIZATION DATE:18/10/25 \n AGE:30\n HEALTH ISSUE:anemia\n ROOM NUMBER:010\n REFERRED DOCTOR:Dr.Akash Shetty\n MEDICAL TESTS TO  BE DONE:Full Blood Count (FBC) ");
         break;
        default:
        printf(" Invalid input \n PLEASE TRY AGAIN");
        break;
        
       
    }
    return 0;
}

