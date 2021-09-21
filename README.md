<Grid.ColumnDefinitions>
            <ColumnDefinition  Width = " 150 " />
            <ColumnDefinition  Width = " * " />
        </Grid.ColumnDefinitions>

        <StackPanel Grid.Column="0" VerticalAlignment="Bottom">
            <Button Content="dssd"></Button></StackPanel>
        <ListView
            Grid.Column="1"
            Grid.Row="1"
            ItemsSource="{Binding ProductList}"
            x:Name="ProductListView">
            <ListView.ItemTemplate>
                <DataTemplate>
                    <Border BorderThickness="1"
                            BorderBrush="Black"
                            CornerRadius="5">
                        <Grid Margin="10" HorizontalAlignment="Stretch">
                            <Grid.ColumnDefinitions>
                                <ColumnDefinition Width="64"/>
                                <ColumnDefinition Width="*"/>
                                <ColumnDefinition Width="100"/>
                            </Grid.ColumnDefinitions>
                            <TextBlock Grid.Column="2"
                                       HorizontalAlignment="Right"
                                Text="{Binding MinCostForAgent}"/>
                            <Grid Grid.Column="1" Margin="5">
                                <Grid.RowDefinitions>
                                    <RowDefinition Height="20"/>
                                    <RowDefinition Height="20"/>
                                    <RowDefinition Height="*"/>
                                </Grid.RowDefinitions>

                                <StackPanel Orientation="Horizontal">
                                    <TextBlock Text="{Binding Title}"/>
                                    <TextBlock Text=" | "/>
                                    <TextBlock Text="{Binding ProductType.Title}"/>
                                </StackPanel>
                                
                                
                                
                            </Grid>
                        </Grid>
                        
                    </Border>
                </DataTemplate>
                
            </ListView.ItemTemplate>
            <ListView.ItemContainerStyle>
                <Style 
            TargetType="ListViewItem">
                    <Style.Triggers>
                        <DataTrigger
                            Binding="{Binding MinSalary}"
                            Value="True">
                            <Setter
                                Property="Background"
                                Value="Khaki"/>
                        </DataTrigger>
                    </Style.Triggers>
                    <Setter 
                Property="HorizontalContentAlignment"
                Value="Stretch" />
                </Style>
            </ListView.ItemContainerStyle>
        </ListView>
        <Grid.ColumnDefinitions>
            <ColumnDefinition  Width = " 150 " />
            <ColumnDefinition  Width = " * " />
        </Grid.ColumnDefinitions>

        <StackPanel Grid.Column="0" VerticalAlignment="Bottom">
            <Button Content="dssd"></Button></StackPanel>
        <ListView
            Grid.Column="1"
            Grid.Row="1"
            ItemsSource="{Binding ProductList}"
            x:Name="ProductListView">
            <ListView.ItemTemplate>
                <DataTemplate>
                    <Border BorderThickness="1"
                            BorderBrush="Black"
                            CornerRadius="5">
                        <Grid Margin="10" HorizontalAlignment="Stretch">
                            <Grid.ColumnDefinitions>
                                <ColumnDefinition Width="64"/>
                                <ColumnDefinition Width="*"/>
                                <ColumnDefinition Width="100"/>
                            </Grid.ColumnDefinitions>
                            <TextBlock Grid.Column="2"
                                       HorizontalAlignment="Right"
                                Text="{B
<Grid>
        <Grid.ColumnDefinitions>
            <ColumnDefinition  Width = " 150 " />
            <ColumnDefinition  Width = " * " />
        </Grid.ColumnDefinitions>

        <StackPanel Grid.Column="0" VerticalAlignment="Bottom">
            <Button Content="dssd"></Button></StackPanel>
        <ListView
            Grid.Column="1"
            Grid.Row="1"
            ItemsSource="{Binding ProductList}"
            x:Name="ProductListView">
            <ListView.ItemTemplate>
                <DataTemplate>
                    <Border BorderThickness="1"
                            BorderBrush="Black"
                            CornerRadius="5">
                        <Grid Margin="10" HorizontalAlignment="Stretch">
                            <Grid.ColumnDefinitions>
                                <ColumnDefinition Width="64"/>
                                <ColumnDefinition Width="*"/>
                                <ColumnDefinition Width="100"/>
                            </Grid.ColumnDefinitions>
                            <TextBlock Grid.Column="2"
                                       HorizontalAlignment="Right"
                                Text="{Binding MinCostForAgent}"/>
                            <Grid Grid.Column="1" Margin="5">
                                <Grid.RowDefinitions>
                                    <RowDefinition Height="20"/>
                                    <RowDefinition Height="20"/>
                                    <RowDefinition Height="*"/>
                                </Grid.RowDefinitions>

                                <StackPanel Orientation="Horizontal">
                                    <TextBlock Text="{Binding Title}"/>
                                    <TextBlock Text=" | "/>
                                    <TextBlock Text="{Binding ProductType.Title}"/>
                                </StackPanel>
                                
                                
                                
                            </Grid>
                        </Grid>
                        
                    </Border>
                </DataTemplate>
                
            </ListView.ItemTemplate>
            <ListView.ItemContainerStyle>
                <Style 
            TargetType="ListViewItem">
                    <Style.Triggers>
                        <DataTrigger
                            Binding="{Binding MinSalary}"
                            Value="True">
                            <Setter
                                Property="Background"
                                Value="Khaki"/>
                        </DataTrigger>
                    </Style.Triggers>
                    <Setter 
                Property="HorizontalContentAlignment"
                Value="Stretch" />
                </Style>
            </ListView.ItemContainerStyle>
        </ListView>
        
    </Grid>
