# android-swipe-listener
Detection of swipe gestures.

```java
// Override method in an Activity
RelativeLayout myLayout = (RelativeLayout) v.findViewById(R.id.<LAYOUT>);
myLayout.setOnTouchListener(new SwipeListener(getActivity()) {

    @Override
    public void onSwipeLeft() {

        // ...
    }
});
```

Check the [original](http://stackoverflow.com/a/19506010/2735839) thread on SO.