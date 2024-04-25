# Rating-Prediction：透過留言評論預測幾顆星 (1-5)
## train.json：五項指標 (ratings、texts、helpful_votes、verified_purchases、titles)
1. "rating": 1.0, 
2. "title": "Bristles fall out, also very stiff", 
3. "text": "The boar bristles fall out. The plastic bristles are so stiff that I am not convinced the boar bristles can even brush through my hair. I do not recommend!", 
4. "helpful_vote": 0, 
5. "verified_purchase": true

## test.json：四項指標 (texts、helpful_votes、verified_purchases、titles)
1. "title": "Do not reccomend",
2. "text": "Thin, cheap.",
3. "helpful_vote": 0,
4. "verified_purchase": true
   
## 預測目標：
- ratings (1-5 顆星)

## 使用模型
- Bert
