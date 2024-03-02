cmake_minimum_required(VERSION 3.5)
project(unsplash-wallpapers)

set(BACKGROUNDS
	default.jpg
	wallpaper-1.jpg
	wallpaper-2.jpg
	wallpaper-3.jpg
	wallpaper-4.jpg
)

install(FILES ${BACKGROUNDS} DESTINATION /usr/share/backgrounds/lingmoos)
