## Il riconoscimento

Ci appoggeremo ad un [sito](https://animal.toolpie.com/) <br> per il riconoscimento degli animali</p>

```python
# get per aprire pagina web
driver.get("https://animal.toolpie.com/")

# l'input dove bisogna inserire l'immagine
searchbar = driver.find_element_by_id("validatedCustomFile")
searchbar.send_keys(photo)

# tasto per inviare l'immagine
submit = driver.find_element_by_id("inputSubmit")
submit.click()
```
