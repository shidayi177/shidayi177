{
     
    for(int i=1;i<num;i++)
    {
        for(int f=num;f>i;f--)
        {
            if(s[f].SCORE>s[f-1].SCORE)
            {
                o=a[f].SCORE;
                a[f].SCORE=a[f-1].SCORE;
                a[f-1].SCORE=o;
                strcpy(j,a[f].NAME);
                strcpy(a[f].NAME,a[f-1].NAME);
                strcpy(a[f-1].NAME,j);
            }
        }
    }
}
