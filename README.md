# android-swipe-listener
Listen for swipe gestures.

```
// Override method in an Activity
RelativeLayout myLayout = (RelativeLayout) v.findViewById(R.id.{LAYOUT});
myLayout.setOnTouchListener(new SwipeListener(getActivity()) {

    @Override
    public void onSwipeLeft() {

        // ...
    }
});
```

Check http://stackoverflow.com/a/19506010/2735839