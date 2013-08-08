

target1 = server
target2 = client

all : $(target1) $(target2)

$(target1) :
	g++ server.cpp -o $(target1) -w

$(target2) :
	g++ client.cpp -o $(target2) -w

clean :
	rm -rf $(target1) $(target2)
