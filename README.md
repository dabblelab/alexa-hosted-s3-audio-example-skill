![](https://raw.githubusercontent.com/rimmi21/alexa-hosted-s3-audio-example-skill/main/assets/image.png)

# Alexa Hosted S3 Audio Skill Example

When you create an [Alexa-Hosted](https://developer.amazon.com/en-US/docs/alexa/hosted-skills/build-a-skill-end-to-end-using-an-alexa-hosted-skill.html) skill, an Amazon S3 bucket is also created for hosting media files. But the files you store in that bucket are not accessible publicly. So, you can't just use the default file URL in your skill, you need a signed URL.

This is an Alexa skill template that provides a starting point for creating a skill that uses the [Alexa-Hosted S3 Audio Utility](https://developer.amazon.com/en-US/docs/alexa/hosted-skills/build-a-skill-end-to-end-using-an-alexa-hosted-skill.html) to quickly store a properly formatted audio file in the hosted s3 media bucket and play it in the skill.

### Using this skill template

1. If you don't have one already, create an [Amazon Developer account](https://developer.amazon.com/).

2. Click the button below to deploy the code for this skill into your Alexa developer account.

   [![Custom badge](https://img.shields.io/endpoint?url=https://badges-shields-io-88j4y07yzimq.runkit.sh)](https://deploy.dabble.dev/deploy/v2/yojf15ci7h)

3. In the Alexa developer console, set the skill's invocation name.

4. Test the skill with an Alexa device that can play video.

   > **NOTE:** You can test the skill in devices like: Echo Dot, Echo Show, Fire TV, some Fire tablets, and other devices.

5. Modify the skill code to use your own stream URL.



