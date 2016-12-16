# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: prossi <marvin@42.fr>                      +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2016/11/16 11:34:52 by prossi            #+#    #+#              #
#    Updated: 2016/11/16 12:27:55 by prossi           ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a

REP_SRCS = ./srcs/

HEAD = ./includes/

SRC = $(REP_SRCS)ft_putchar.c $(REP_SRCS)ft_putstr.c $(REP_SRCS)ft_strcmp.c \
		$(REP_SRCS)ft_strlen.c $(REP_SRCS)ft_swap.c

OBJ = ft_putchar.o ft_putstr.o ft_strcmp.o ft_strlen.o ft_swap.o

all: $(NAME)

$(NAME):
	gcc -Wall -Wextra -Werror -I $(HEAD) -c $(SRC)
	ar rc $(NAME) $(OBJ)
	ranlib $(NAME)

clean:
	/bin/rm -f $(OBJ)

fclean: clean
	/bin/rm -f $(NAME)

re: fclean all
