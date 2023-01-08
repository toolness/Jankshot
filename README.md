This camera app was created to satisfy the following need.

I, Atul Varma, don't usually need the 12 terapixel photos that my cell phone is capable of taking.

Most of the time, I just see a funny sign on the street and want to send it to a buddy. Yet doing this with the default camera app captures it at full 12 terapixel resolution, and sometimes it's even _sent_ at that resolution. And then 6 months later my phone and/or email account is bugging me because I've run out of space filling it with hundreds of 12 terapixel photos, and I don't want to have to sift through them all to delete the ones that are just funny signs.

So Jankshot is an app that takes a photo like it's a digital camera from 1997.  It's janky, but it's also like a 100k JPEG or something, my phone can store billions of them. Perfect for snapping a pic of a funny sign--but if you want to take a masterpiece that can fit on a billboard, use a different camera app.

## Quick start

I dunno, I wrote this app almost a year ago and I'm just updating this README now before open-sourcing it. I think you have to install Android Studio or something.

You may also need to set the following environment variable because Android development is extremely confusing:

```
ANDROID_SDK_ROOT=C:\Users\YOUR_USER_NAME\AppData\Local\Android\Sdk
```

## References

* [Getting Started with CameraX](https://developer.android.com/codelabs/camerax-getting-started) - Nice series of tutorials on the basics of using the camera, which this app is based off.
* [View Binding](https://developer.android.com/topic/libraries/view-binding) - Used this to make it easier to reference views in the layout XML.

## License

Everything in this repository that isn't provided by a third party is licensed under [CC0 1.0 Universal](./LICENSE.md) (public domain).
