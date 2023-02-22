CC = gcc
CFLAGS =  -Wall -Wextra -Werror
SOURCES = my_ls.c
TARGET = my_ls

$(TARGET):$(SOURCES)
	$(CC) $(CFLAGS) -o $@ $^ 
 
.PHONY: fclean

fclean:
	@rm -r $(TARGET)