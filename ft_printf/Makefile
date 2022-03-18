# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: fde-albe <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/03/07 15:08:12 by fde-albe          #+#    #+#              #
#    Updated: 2022/03/07 15:57:15 by fde-albe         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

SRCS		=	ft_printf.c ft_putchar.c ft_putsigned.c \
				ft_putstr.c ft_puthex.c  ft_putunsigned.c\
				ft_putptr.c ft_strlen.c ft_calloc.c \
				ft_bzero.c ft_memset.c ft_itoa.c \
				ft_uitoa.c ft_puthexup.c\

OBJS		= $(SRCS:.c=.o)

CC			= gcc
RM			= rm -f
CFLAGS		= -Wall -Wextra -Werror -I.

NAME		= libftprintf.a

all:		$(NAME)


$(NAME):	$(OBJS)
			ar rcs $(NAME) $(OBJS)

clean:
			$(RM) $(OBJS)

fclean:		clean
			$(RM) $(NAME)

re:			fclean $(NAME)
