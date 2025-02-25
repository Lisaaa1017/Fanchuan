# Tiktok-Trump Dataset

## Final_user_comment_video.xlsx
### 1. id: the new unique sequence of comment
### 2. user_id: user id of people who post this comment
### 3. parent_user_id: user id of people who post the parent comment
### 4. comment_id: comment id
### 5. parent_comment_id: comment id of parent comment
### 6. user: user information of this comment
### 7. parent_user: user information of people who post the parent comment
### 8. content: the content of this comment
### 9. parent_content: the content of parent comment
### 10. parody: label of parody
0 : non-parody;
1 : parody
### 11. support: label of sentiment
0 : neutral;
1 : positive;
2: negative


## users_sentiment.xlsx
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
