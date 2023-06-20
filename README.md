# correccionTPHaskell
Corrección TP N°2 - Haskell (Ejercicio Año Bisiesto)

esBisiesto :: Int -> Bool
esBisiesto anio =  ((anio `mod` 4) == 0 && (anio `mod` 100) /= 0) (anio `mod` 400) == 0 ||
