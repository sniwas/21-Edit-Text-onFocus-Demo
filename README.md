# 21-Edit-Text-onFocus-Demo

editText.setOnFocusChangeListener(new View.OnFocusChangeListener() {
            @Override
            public void onFocusChange(View v, boolean hasFocus) {
                if(hasFocus) {
                    editText.setTextColor(getResources().getColor(R.color.red));
                }
                else{
                    editText.setTextColor(getResources().getColor(R.color.black));
                }
            }
        });
        
        
OnStart:
![image](https://user-images.githubusercontent.com/122344020/235820858-1c9bc9ae-8fe8-49ca-841f-2d64e11b30f6.png)

During onFocus : 
![image](https://user-images.githubusercontent.com/122344020/235820880-5683a7f3-3f27-45c2-a698-feda95e65830.png)
