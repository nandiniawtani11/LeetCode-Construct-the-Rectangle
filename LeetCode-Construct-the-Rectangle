class Solution {
    public List<Integer> factors(int n)
    {
        List<Integer> list=new ArrayList<>();
        for (int i=2;i<=n/2;i++)
            if (n%i==0)
                list.add(i);
        return list;
                
    }
    public int[] constructRectangle(int area) {
        int[] arr=new int[2];
         List<Integer> list1=new ArrayList<>();
        list1.addAll(factors(area));
         int len=list1.size();
        if(len==0)
        {
            arr[0]=area;
            arr[1]=1;
            return arr;
        }
       
        else if(len%2==0)
        {
            arr[0]=list1.get(len/2);
            arr[1]=list1.get((len/2)-1);
        }
        else
        {
            arr[0]=arr[1]=list1.get(len/2);
        }
       
        
        return arr;
    }
}
