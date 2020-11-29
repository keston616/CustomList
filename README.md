# CustomList
        public int IndexOf(T item)
        {
            int indexOf = 0;
            for (int i = 0; i < this.arr.Length; i++)
            {
                if (arr[i].Equals(item)) indexOf = i;
            }
            return indexOf;
        }
