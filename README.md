
```char	*find_key(t_dict *key, t_dict *alpha, char *key, int index)
{
	int	i;

	i = 0;
	while (!ft_strcmp(dict_data[i].key, ft_strfbct(index * 3)))
	{
		if (dict_data[i].key == "END")
			return("END");
		i++;
	}
	return(dict_data[i].alpha);```
}

```char	*ft_strfbct(int index)
{
	char 	*str;
	int		i;
	int		ii;
	
	i = 0;
	str = malloc((index + 1) * sizeof(char))
	str[index] = '\0';
	str[i] = '1';
	i++;
	while (str[i] != '\0')
		str[i++] = '0';
	return (str);
}```