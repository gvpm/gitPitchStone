#HSLIDE?image=assets/images/bg2.png

## <span class="pd-gray">Título</span>
### <span class="pd-gray">Subtítulo</span>

#VSLIDE?image=assets/images/bg3.png

<img src="assets/images/you.png" alt="You" style="width: 200px;"/>

### <span class="pd-gray">Seu Nome</span>
##### <span class="pd-gray">Texto</span>

#HSLIDE?image=assets/images/bg3.png

## <span class="pd-gray">Codes</span>

#VSLIDE?image=assets/images/bg3.png

```c#
public static AbstractBusinessProcessor BuildBusinessProcessor(AffiliationOperationEnum operation) {
            switch (operation) {
                case AffiliationOperationEnum.InsertAffiliation:
                case AffiliationOperationEnum.UpdateAffiliation:
                case AffiliationOperationEnum.QueryAffiliation: {
                        return new AffiliationProcessor();
                    }

                case AffiliationOperationEnum.InsertAssociation:
                case AffiliationOperationEnum.UpdateAssociation:
                case AffiliationOperationEnum.QueryAssociation: {
                        return new AssociationProcessor();
                    }

                case AffiliationOperationEnum.InsertBin:
                case AffiliationOperationEnum.UpdateBin:
                case AffiliationOperationEnum.QueryBin: {
                        return new BinProcessor();
                    }

                default:
                    return null;
            }
  ```
@[1]
@[3]
@[5-7]
  
