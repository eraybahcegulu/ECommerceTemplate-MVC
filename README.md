# ECommerceTemplate

- List<Product> phoneProducts = _productRepository.GetAll(includeProps: "ProductType").Where(p => p.ProductType != null && p.ProductType.Type == "Phone").ToList();
- includeProps > Foreign Key

- @model List<Product>
   @if (Model.Count > 0)
{

}
else
{

}
