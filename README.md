# MicroFlag

Link: https://olaknowct.github.io/MicroFlag/index.html

## Description

- The Flag APP, Shows the Flag and its details based from the button clicked

## About

- The Project is used for educational purposes only, its part of the lesson i took from Jonas.
- As part of my learnings and would benefit me, I've listed down here **(See features section)** all the PSEUDO Code, SUMMARY and Feautures from this Project
- The Project emphasize the difference of Asynchronous and Synchronous, why it was used and advantage over then catch method. 
- Buttons attribute are preset, we can configure the map details depend on what country you wnat to display by passing query parameter from the API Endpoint.

## Concepts Tackled
- Old school asynchronous call (AJAX)
- Async and await
- CallBack hell
- Flat then catch (Chaining promises)
- Try and Catch
- Async Await
- Error handling for try and catch, Async Await.
- Conccurent Error, 

### Features, PSEUDO, Summary And Learnings

	- Get Current Position using geolocation API
	- Detect country details, Using the coordinates received from the geolocation API
		○ Used geocode API 
			§ Documentation : https://geocode.xyz/api
	- Get Flag details using the data from the result of geocode API
		○ Used Rest Countries
			§ Documentation : http://restcountries.eu/
  	- Update DOM 

### New Featues and Improvements
	- Refactor event handler
	- Add 4 buttons for emphasizing the following
		○ A country that doesnt have any neighbour
		○ A Country that has neighbours
	- Used event delegation to miximize conding
	- Used event target (Bubbles effect)

   
