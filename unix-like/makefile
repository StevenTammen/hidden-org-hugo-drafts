build-other-archetypes: npage nlinks nproject

npage: npost
	cp npost npage
	sed -i "s/posts/pages/g" npage
	
nlinks: npost
	cp npost nlinks
	sed -i "s/posts/links/g" nlinks
	
nproject: npost
	cp npost nproject
	sed -i "s/posts/projects/g" nproject

clean:
	rm npage nlinks nproject