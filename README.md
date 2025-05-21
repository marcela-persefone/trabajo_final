https://mybinder.org/v2/gh/marcela-persefone/trabajo_final/35ca49f1d11b2fbe6954ab42e731ed692aff9011?urlpath=lab%2Ftree%2Ftrabajo.ipynb

https://mybinder.org/v2/gh/marcela-persefone/trabajo_final/fd35596ee4a4d17113ee7fc1863f19b18c1040fb?urlpath=lab%2Ftree%2FModelo%20(1).ipynb


Nuevo:       https://mybinder.org/v2/gh/marcela-persefone/trabajo_final/18ed851d424eba52cf9be9f64e2b9c7ba44e2bb3?urlpath=lab%2Ftree%2FModelo%20(1).ipynb

# Boxplot del valor promedio de ítems por transacción vs preferencia de compra
plt.figure(figsize=(8, 5))
sns.boxplot(data=df, x="compra_online", y="avg_items_per_transaction")
plt.title("Promedio de Ítems por Transacción vs Preferencia de Compra")
plt.xlabel("Compra Online (1=Sí)")
plt.ylabel("Ítems por Transacción")
plt.grid(True)
plt.show()
