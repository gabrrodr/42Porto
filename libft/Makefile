# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: gabrrodr <gabrrodr@student.42.fr>          +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2023/04/17 17:01:03 by gabrrodr          #+#    #+#              #
#    Updated: 2023/04/26 12:27:42 by gabrrodr         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

MDT =	ft_atoi.c \
	ft_bzero.c \
	ft_calloc.c \
	ft_isalnum.c \
	ft_isalpha.c \
	ft_isascii.c \
	ft_isdigit.c \
	ft_isprint.c \
	ft_itoa.c \
	ft_memchr.c \
	ft_memcmp.c \
	ft_memcpy.c \
	ft_memmove.c \
	ft_memset.c \
	ft_putchar_fd.c \
	ft_putendl_fd.c \
	ft_putnbr_fd.c \
	ft_putstr_fd.c \
	ft_split.c \
	ft_strchr.c \
	ft_strdup.c \
	ft_striteri.c \
	ft_strjoin.c \
	ft_strlcat.c \
	ft_strlcpy.c \
	ft_strlen.c \
	ft_strmapi.c \
	ft_strncmp.c \
	ft_strnstr.c \
	ft_strrchr.c \
	ft_strtrim.c \
	ft_substr.c \
	ft_tolower.c \
	ft_toupper.c \

BNS =	ft_lstnew.c \
	ft_lstadd_front.c \
	ft_lstsize.c \
	ft_lstlast.c \
	ft_lstadd_back.c \
	ft_lstdelone.c \
	ft_lstclear.c \
	ft_lstiter.c \
	ft_lstmap.c \
	
CC = cc

RM = rm -f

CFLAGS = -Wall -Wextra -Werror

OBJ_MDT = $(MDT:.c=.o)
OBJ_BNS = $(BNS:.c=.o)

NAME = libft.a

all : $(NAME)

$(NAME): $(OBJ_MDT)
	ar rcs $(NAME) $(OBJ_MDT)

bonus: $(OBJ_MDT) $(OBJ_BNS)
	ar rcs $(NAME) $(OBJ_BNS) $(OBJ_MDT)
	
clean:
	$(RM) $(OBJ_MDT) $(OBJ_BNS)
	
fclean: clean
	$(RM) $(NAME)
	
re : fclean $(NAME)
