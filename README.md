# rev-stack
class Solution{
public:
    void Reverse(stack<int> &St){
       vector<int>ans;
       while(!St.empty())
       {
           ans.push_back(St.top());
           St.pop();
       }
       for(int i=0;i<ans.size();i++)
       {
           St.push(ans[i]);
       }
      
    }
       
};
