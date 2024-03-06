
# STACK IMPLEMENTATIOM USING ARRAY


#include<stdio.h>
#include<stdlib.>


struct queue {


    int size;

    int top;

    int * arr;
};

int main ();  {
 
   struct queue *sp = (struct queue *) malloc(sizeof(struct queue));

    queue size = 5;

    queue top = -1;

    queue arr = (int *)malloc(queue size * sizeof(int));

    printf("queue has been created successfully\n");
    return 0;
}

