# Instagram-Batch-Unfollower
Use Python to unfollow multiple people off of Instagram at a time. This is one of the only valid and unpaid ways to automate Instagram unfollowing

## Dependencies
Depends on the `InstagramAPI` module, which you can [find out about here](https://github.com/LevPasha/Instagram-API-python).

To install InstagramAPI module via pip:
```
pip install InstagramAPI
```

## How to Run
Simply run *batch_unfollow.py* in terminal or Command Prompt. There are optional arguments which can be used:

*-u*  changes how many users you would like to unfollow at one time

*-t* changes the maximum interval delay in seconds for unfollowing users. The delay will be randomized within the interval

**Example use:**
```
python batch_unfollow.py 'your_username' 'your_password' -u 50 -t 10
```