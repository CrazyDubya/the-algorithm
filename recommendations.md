# X Recommendation Algorithm: Analysis and Recommendations

This document provides an analysis of the X recommendation algorithm and offers recommendations for users who want to increase their visibility and reach on the platform. The analysis is based on a review of the open-source code, with a focus on the `user-signal-service` and the ranking models.

## How the Algorithm Works: A High-Level Overview

The X recommendation algorithm is designed to surface relevant and engaging content to users. It does this by analyzing a variety of signals that indicate a user's interest in a particular post or account. These signals can be positive (e.g., likes, retweets) or negative (e.g., reports, mutes).

The core of the recommendation system is a "heavy ranker" model that predicts the probability of a user engaging with a post. This model is trained on a massive dataset of user interactions and is constantly being updated to improve its accuracy.

### The Light Ranker: A First Pass Filter

Before a post is sent to the heavy ranker, it is first evaluated by a "light ranker" model. The light ranker is a simpler model that is designed to quickly and efficiently filter out low-quality or irrelevant content.

The light ranker uses a variety of signals to evaluate a post, including:

*   **Engagement Metrics:** The light ranker looks at the same basic engagement metrics as the heavy ranker, such as likes, retweets, and replies.
*   **Media and Links:** The light ranker gives a boost to posts that contain images, videos, or links.
*   **Content Quality:** The light ranker uses a "text score" to evaluate the quality of the text in a post. This score is based on factors such as offensiveness, content entropy, "shout" score, length, and readability.
*   **User Reputation:** The light ranker considers the reputation of the author of the post, which is based on their "tweepcred" score.
*   **Negative Signals:** The light ranker penalizes posts that are flagged as offensive, sensitive, or spammy.

## The Ideal Post: Maximizing Positive Signals

To maximize the visibility of your posts, you should aim to create content that generates a high number of positive engagement signals. The most important signals are:

*   **Favorites (Likes):** This is one of the strongest positive signals. The more likes a post receives, the more likely it is to be recommended to other users.
*   **Retweets:** Retweets are another powerful signal that a post is interesting and valuable.
*   **Replies:** Replies indicate that a post is sparking conversation and engagement.
*   **Video Views:** For video content, the algorithm prioritizes videos that are watched for a significant amount of time. Aim for videos that are at least 10 seconds long and try to capture the viewer's attention in the first few seconds.
*   **Good Clicks:** The algorithm tracks how long a user dwells on a post. If a user spends at least 2 seconds on a post, it's considered a "good click" and a positive signal.

In addition to maximizing positive signals, you should also avoid generating negative signals. The most important negative signals are:

*   **"Don't like" clicks:** When a user clicks the "Don't like" button on a post, it sends a strong negative signal to the algorithm.
*   **"See fewer" clicks:** Similar to the "Don't like" button, the "See fewer" button tells the algorithm that a user is not interested in a particular type of content.
*   **Reports:** Reporting a post is the strongest negative signal a user can send.

## The Ideal Activity: Being a Positive and Engaged User

The algorithm also considers a user's overall activity on the platform. To increase your visibility, you should aim to be an active and engaged user who contributes positively to the platform. The most important activities are:

*   **Following other accounts:** Following other accounts helps the algorithm understand your interests and recommend relevant content to you.
*   **Visiting other users' profiles:** Visiting other users' profiles, especially repeatedly, is a positive signal that you are interested in their content.
*   **Engaging with other users' content:** Liking, retweeting, and replying to other users' posts helps the algorithm understand what kind of content you find interesting.

Just as with posts, you should also avoid negative activities, such as:

*   **Being blocked or muted:** Being blocked or muted by other users is a strong negative signal that can significantly reduce your visibility on the platform.

## Key Takeaways

*   **Focus on creating high-quality, engaging content that sparks conversation.**
*   **Encourage your followers to like, retweet, and reply to your posts.**
*   **Use video to capture your audience's attention.**
*   **Be an active and engaged user who contributes positively to the platform.**
*   **Avoid posting content that is likely to be reported or hidden.**
