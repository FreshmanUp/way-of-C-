int arr[8] = { 23,12,34,45,56,67,78,10 };
int len = sizeof(arr) / sizeof(arr[0]);
// 需要排序的轮数：len - 1
// 每轮需要比较的次数：len - 轮数 - 1
for (int i = 0; i < len - 1; i++)
{
	for (int j=0;j<len-1-i;j++)
	{
		if (arr[j] > arr[j + 1])
		{
			int temp = arr[j + 1];
			arr[j + 1] = arr[j];
			arr[j] = temp;
		}
	}
}
for (int i = 0; i < len ; i++)
{
	cout << arr[i] << endl;
}
