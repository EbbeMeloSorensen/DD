For at konfigurere til hexagonal tile mode:

1) I constructoren MainWindowViewModel
   - Sæt engine til SimpleEngine
   - Sæt enginens BoardTileMode til Hexagonal
2) I MainWindow.xaml.cs
   - Udkommenter BoardViewSquares user controlen
   - Indkommenter BoardViewHexagons user controlen

-----------------------------------------------------

For at konfigurere til square tile mode:

1) I constructoren MainWindowViewModel
   - Sæt engine til SimpleEngine
   - Sæt enginens BoardTileMode til Hexagonal
2) I MainWindow.xaml.cs
   - Udkommenter BoardViewSquares user controlen
   - Indkommenter BoardViewHexagons user controlen
