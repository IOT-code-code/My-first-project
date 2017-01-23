# My-first-project
冒泡排序法  //  相邻两个元素比较，第一圈，最值出现在最后位

int []maopao={1,1,24,45,63,66,734,73,743,872,73};
	for(int x=0;x<maopao.length-1;x++)
	{     
		for(int y=0;y<maopao.length-1-x;y++)//-x让没每一次比较的元素减少，-1避免·角标越界
	{
		int m;
		if(maopao[y]<maopao[y+1])
			{
			 m=maopao[y+1];
			 maopao[y+1]=maopao[y];
			 maopao[y]=m;
			}		
	}
	}
		for(int x=0;x<maopao.length;x++)
		{
		   System.out.print(maopao[x]+"，");
		}
