# MembuatSplashScreen
 Splash Screen Android dengan Menggunakan Handler

 Script handler yang digunakan untuk membuat splash screen pada Android sederhananya adalah sebagai berikut

```
HDL = new Handler();

HDL.postDelayed(new Runnable() {
    @Override
    public void run() {
        startActivity(new Intent(MainActivity.this, SecondActivity.class));
        finish();
    }
}, 2000);
```

2000 pada bagian akhir dari handler postDelayed di atas maksudnya adalah 2000 ms. Artinya splash screen akan berjalan dalam waktu 2000 ms atau 2 detik.