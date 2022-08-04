NAME =	libftprintf.a

SRCS =	printf_utils.c ft_printf.c

OBJS = $(SRCS:.c=.o)

CC =	gcc
RM =	rm -f
CFLAGS =	-Wall -Wextra -Werror

all: $(NAME)

$(NAME):
	$(CC) $(CFLAGS) -c $(SRCS)
	ar rc $(NAME) $(OBJS)

clean:
	$(RM) $(OBJS)

fclean: clean
	$(RM) $(NAME)

re: fclean all

.PHONY: clean fclean all re
