SRC = main.cpp 
OBJ = $(SRC:.cpp=.o)
NAME =  HiThisIsBrain
CXX = c++
CXXFLAGS = -Wall -Wextra -Werror -std=c++98

all: $(NAME)

$(NAME): $(OBJ)
	$(CXX) $(CXXFLAGS) $(OBJ) -o $(NAME)

%.o: %.cpp
	$(CXX) $(CXXFLAGS) -c $< -o $@

clean:
	rm -f $(OBJ)

fclean: clean

re: fclean all

.PHONY: all clean fclean re	