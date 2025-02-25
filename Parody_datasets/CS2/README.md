# CS2 Dataset

## Final_user_comment_video.xlsx
### 1. id: the new unique sequence of comment
### 2. comment_id: comment id
### 3. parent_comment_id: comment id of parent comment
### 4. user_id: user id of people who post this comment
### 5. parent_user_id: user id of people who post the parent comment
### 6. video_id: video id
### 7. parent_user: user information of people who post the parent comment
### 8. user: user information of this comment
### 9. parent_content: the content of parent comment
### 10. content: the content of this comment
### 11. support: label of sentiment
0 : neutral;
1 : support g2;
2 : oppose g2;
3 : support navi;
4 : oppose navi
### 12. parody: label of parody
0 : non-parody;
1 : parody

## users_sentiment_new.xlsx
### 1. node_id: the new unique sequence of user
### 2. user_id: user id
### 3. content: all comments from this user
### 4. support: label of sentiment of this user
0 : neutral;
1 : support g2;
2 : oppose g2;
3 : support navi;
4 : oppose navi
### 5. all_support: label of sentiment to each comment from this user
0 : neutral;
1 : support g2;
2 : oppose g2;
3 : support navi;
4 : oppose navi
