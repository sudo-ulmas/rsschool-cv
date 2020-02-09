# **Resume**
## *Ulmasbek Rakhmatullaev*
### *rakhmatullaevulmas@gmai.com*
### *+998977690244*
***
## **Objective:**
To gain experience in frontend web development in a software
company that requires intelligent employees and offers opportunities for
advancement for young developers.
***
## **Skills:**
* Dart (Flutter)
* C, C++, Assembly Language
* Java, OOP, SQL
* HTML5, CSS3, JavaScript
* Python (Django) 
* Git
***
## **Code Examples:** 
```
 Future<List<Movie>> updateUpcomingMovies() async{
    if(coming_movies.length==0){
   final response = await http.get(Uri.encodeFull(comingSoonUrl),
        headers: {"Accept": "application/json"});

        if (response.statusCode == 200) {
     
      var jSon = json.decode(response.body);
      data = jSon["results"];
      for (int i = 0; i < data.length; i++) {
        Movie m = new Movie(
          id: data[i]["id"],
          overview: data[i]["overview"],
          title: data[i]["title"],
          rating: data[i]["vote_average"],
          duration: data[i]["id"],
          premiereDate: data[i]["release_date"],
          image: "https://image.tmdb.org/t/p/w500" + data[i]["poster_path"],
        );
        coming_movies.add(m);
```
***
## **Experience:**
### Freelancer at Upwork.com
#### May 2019 - Sep 2019 
Created mobile app ([QuranApp](https://github.com/ulmas97/quranApp.git)) for reading a quran daily using Flutter.

***
## **Education:**
### Inha University in Tashkent, Faculty of Computer Sciences
#### Entered date: 2016
#### Expected Graduation: 2020
#### Cumulative GPA: 3.6/4.5
#### Included to Dean's List
***
## **English:** 
### Advanced Level
### IELTS - 6.0 in 2016

***
