# Alibaba-Math Dataset

## Final_user_comment.xlsx
### 1. id: comment id
### 2. user_id: user id of people who post this comment
### 3. parent_user_id: user id of people who post the parent comment
### 4. node_id: poster id
### 5. poster: content of poster
### 6. parent_user: user information of people who post the parent comment
### 7. user: user information of this comment
### 8. parent_content: the content of parent comment
### 9. content: the content of this comment
### 10. support: label of sentiment
0 : neutral;
1 : positive;
2: negative
### 11. parody: label of parody
0 : non-parody;
1 : parody

## users_sentiment_new.xlsx
### 1. node_id: the new unique sequence of user
### 2. user_id: user id
### 3. content: all comments from this user
### 4. support: label of sentiment of this user
0 : neutral;
1 : positive;
2: negative
### 5. all_support: label of sentiment to each comment from this user
0 : neutral;
1 : positive;
2: negative
